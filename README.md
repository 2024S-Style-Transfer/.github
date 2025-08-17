# [2024S 종합설계프로젝트1] VisualFable
<br><br><br>
<div align="center">
  <img width="300" alt="Icon@2x" src="https://github.com/2024S-Style-Transfer/visual-fable-front/assets/88702441/cdf9f17b-ba5e-485a-b76a-d5a23b80926d">
</div>
<br><br><br>

## About

> 해당 프로젝트는 종합설계프로젝트1에서 진행 중이며, `일관성있는 스토리 이미지 생성 연구`를 활용한 서비스입니다.<br>
> 개발기간 : 2024.03 ~ 2024.06

<br><br>

**당신이 상상한 세계를 생성할 수 있는 visual fable을 만나보세요**

 유저가 원하는 스타일의 이미지를 최대 5장까지 자유롭게 생성할 수 있습니다. <br>
유저의 프롬프트 입력을 바탕으로 생성된 예시 이미지를 통해 원하는 스타일을 선택할 수 있습니다.

**각 이미지는 스타일의 일관성을 유지합니다.**

 생성된 이미지들은 선택된 예시 이미지와 유사한 스타일로 일관성을 유지합니다. <br>
 따라서 긴 이야기에 필요한 여러장의 삽화 생성에 유용하게 사용할 수 있습니다. <br><br>

---
<br>

## Components

* `Home` : 유저의 입력을 바탕으로 새로운 이미지를 생성합니다
  * `예시 이미지 게시` : 유저가 입력한 프롬프트를 바탕으로 장르를 구분하여 예시 이미지를 선택합니다. 
  * `이미지 생성` : 유저가 선택한 예시 이미지와 프롬프트들을 바탕으로 최대 5장의 일관성 있는 이미지를 생성합니다.
  * `생성 이미지 게시` 

* `About Us` : 서비스에 대해 소개합니다.
* `API Docs` : API 스펙 문서를 게시합니다.
<br><br>

---
<br>

## Requirements


---
## Service Architecture

### Service Client ⭤ Service Server ⭤ Model Server

- [Service Client](https://github.com/2024S-Style-Transfer/visual-fable-front)
- [Service Server](https://github.com/2024S-Style-Transfer/Server_Repo/tree/dev/serviceServer)
- [Model Server](https://github.com/2024S-Style-Transfer/Server_Repo/tree/dev/modelServer)

### UI 설계
[화면 flow 설계 & 화면 목록.pdf](https://github.com/user-attachments/files/15855977/README.GUI.pdf)

---
<br>

## Contributors
<br>
<table align="center">
  <tr height="140px">
    <td align="center">
      <a href="https://github.com/Climier-code"><img height="100px" width="100px" src="https://avatars.githubusercontent.com/u/55488800?v=4"/></a>
      <br />
      <a href="https://github.com/Climier-code">🔹강종연</a>
    </td>
    <td align="center">
      <a href="https://github.com/msm11"><img height="100px" width="100px" src="https://avatars.githubusercontent.com/u/128119495?v=4"/></a>
      <br />
      <a href="https://github.com/msm11">🔹명세민</a>
    </td>
    <td align="center">
      <a href="https://github.com/touhou09"><img height="100px" width="100px" src="https://avatars.githubusercontent.com/u/91013383?v=4"/></a>
      <br />
      <a href="https://github.com/touhou09">🔹유승주</a>
    </td>
    <td align="center">
      <a href="https://github.com/WillowSY"><img height="100px" width="100px" src="https://avatars.githubusercontent.com/u/88702441?v=4"/></a>
      <br />
      <a href="https://github.com/WillowSY">🔹이서영</a>
    </td>
  </tr>
</table>

<br><br>

---
## 내부 문서 모음
- [Github Project & 이슈 관리](https://github.com/orgs/2024S-Style-Transfer/projects/1)
- [Service Client 실행 가이드 및 관련 내용](https://github.com/2024S-Style-Transfer/visual-fable-front/blob/main/README.md)
- [Service Server API 문서](https://github.com/2024S-Style-Transfer/Server_Repo/blob/dev/serviceServer/Guide.md)
- [Model Server 실행 가이드 및 API 문서](https://github.com/2024S-Style-Transfer/Server_Repo/blob/dev/modelServer/Guide.md)
---

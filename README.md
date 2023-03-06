# 인터페이스 챗봇 리팩토링
<img src="https://user-images.githubusercontent.com/44095919/223133828-905449b1-968f-43bc-9690-a7fb3a1590c5.png" width="25%"><br>
<b>▲인터페이스 챗봇 프로필</b>

## 팀원
<table>
  <tr align="center">
    <td width="150">
      <div class="profile" align="center">
        <img src="https://avatars.githubusercontent.com/u/41150708?v=4" width = "70" style = "border-radius: 25px"/>
        <br>
        <h6>인터페이스 31기<br>전자정보통신공학과</h6>
      </div>
    </td>
    <td width="150">
      <div class="profile" align="center">
        <img src="https://avatars.githubusercontent.com/u/44095919?v=4" width = "70" style = "border-radius: 25px"/>
        <br>
        <h6>인터페이스 35기<br>소프트웨어학과</h6>
      </div>
    </td>
    <td width="150">
      <div class="profile" align="center">
        <img src="https://avatars.githubusercontent.com/u/110271852?v=4" width = "70" style = "border-radius: 25px"/>
        <br>
        <h6>인터페이스 35기<br>데이터사이언스학과</h6>
      </div>
    </td>  
  </tr>
  
  <tr algin="center">
    <td width="150">
      <div class="profile" align="center">
        <a href="https://github.com/sw0501">박상욱</a>
      </div>
    </td>
    <td width="150">
      <div class="profile" align="center">
        <a href="https://github.com/geonbly327">김건민</a>
      </div>
    </td>
    <td width="150">
      <div class="profile" align="center">
        <a href="https://github.com/ierkgus">김소희</a>
      </div>
    </td>
  </tr>
  
  <!--<tr algin="center">
    <td width="150">
      <div class="profile" align="center">
        <h6>인터페이스 31기<br>전자정보통신공학과</h6>
      </div>
    </td>
    <td width="150">
      <div class="profile" align="center">
        <h6>인터페이스 35기<br>소프트웨어학과</h6>
      </div>
    </td>
    <td width="150">
      <div class="profile" align="center">
        <h6>인터페이스 35기<br>데이터사이언스학과</h6>
      </div>
    </td>
  </tr>-->
</table>

## 리팩토링 목적
1. 기존 인터페이스 챗봇의 경우 동아리 서버로 운영하는데 어려움이 있음
2. 사용 기능이 한정적이며 Flask로 구현 시 기능의 디자인적 요소를 구현하는 것이 복잡함
3. 시나리오로 기능을 구현하는 경우 디자인이 직관적이며 스킬 서버가 필요없음

## 리팩토링 기능
<table align="center">
  <tr align="center">
    <td width="250">
      <img src="./image/intro.jpg" alt="동아리 소개" width="250">
    </td>
    <td width="250">
      <img src="./image/event.jpg" alt="행사 소개" width="250">
    </td>
    <td width="250">
      <img src="./image/apply.jpg" alt="지원방법" width="250">
    </td>
    <td width="250">
      <img src="./image/clubroom.jpg" alt="동아리방" width="250">
    </td>
  </tr>
  
  <tr align="center">
    <td>
      <b>▲동아리 소개</b>
    </td>
    <td>
      <b>▲행사 소개</b>
    </td>
    <td>
      <b>▲지원방법</b>
    </td>
    <td>
      <b>▲동아리방</b>
    </td>
  </tr>
</table>

<table align="center">
  <tr align="center">
    <td width="250">
      <img src="./image/dues.jpg" alt="회비 안내" width="250">
    </td>
    <td width="250">
      <img src="./image/link.jpg" alt="링크 안내" width="250">
    </td>
    <td width="250">
      <img src="./image/results.jpg" alt="전년도 작품" width="250"
    </td>
    <td width="250">
      <img src="./image/help.jpg" alt="도움말" width="250">
    </td>
  </tr>
  
  <tr align="center">
    <td>
      <b>▲회비 안내</b>
    </td>
    <td>
      <b>▲링크 안내</b>
    </td>
    <td>
      <b>▲전년도 작품</b>
    </td>
    <td>
      <b>▲로그인 화면</b>
    </td>
  </tr>
</table>

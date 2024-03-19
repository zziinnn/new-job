![header](https://capsule-render.vercel.app/api?type=Venom&color=auto&height=300&section=header&text=Hellow&fontSize=90)

# 📂 김연진 포트폴리오

> 김연진(Yeonjin Kim) - zziinnn 포트폴리오 
<br />

# 🖋 Intro
> 안녕하세요! ***"도움이 되는 직원으로 성장하고 싶은"*** 김연진입니다. <br />
> 최근 2년 동안 잡코리아의 UI 개발 부서에서 구축 및 유지보수 작업을 통해 퍼블리셔로서의 역량을 키워왔으며,  <br />
> 배움을 통한 즐거움과 협업의 가치를 이해하며 지속적으로 성장하고 있습니다.
<br />

# 🖥 Projects
>  
> 
### ✔ 프로필 등록
> - 담당업무 : 프로필 등록을 위한 팝업창 구축 및 유지보수
> - 퍼블리싱 : 100%
> - 작업기간 : 2개월
> - Skill : ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
<br />
 
- 주요코드

``` C
var selectboxOptions = document.querySelectorAll('.line-box .selectbox-option');
var lineBoxes = document.querySelectorAll('.line-box');

//외부 클릭 시 리스트 닫기
document.addEventListener('mouseup', function (e) {
    lineBoxes.forEach(function (lineBox) {
        if (!lineBox.contains(e.target)) {
            lineBox.classList.remove('on');
            var otherSelectboxOptions = lineBox.querySelectorAll('.selectbox-option');
            otherSelectboxOptions.forEach(function(otherSelectboxOption) {
                otherSelectboxOption.classList.remove('active');
            });
        }
    }); 
});

//selectbox-option 리스트 열김 겹침 제어 + 열고 닫기 + arrow iocn 제어
lineBoxes.forEach(function(lineBox) {
    lineBox.addEventListener('click', function() {
        lineBox.classList.toggle('on');
        selectboxOptions.forEach(function(selectboxOption) {
            selectboxOption.classList.toggle('active');
        });
        lineBoxes.forEach(function(otherLineBox) {
            if (otherLineBox !== lineBox) {
                otherLineBox.classList.remove('on');
                var otherSelectboxOptions = otherLineBox.querySelectorAll('.selectbox-option');
                otherSelectboxOptions.forEach(function(otherSelectboxOption) {
                  otherSelectboxOption.classList.remove('active');
                });
            }
        });
    });
});
```

###### 갼략 캡쳐본
<table>
  <tbody>
    <tr>
      <td>
        <img align="center" src="./images/img1.png" width="250">
      </td>
      <td>
        <img align="center" src="./images/img2.png" width="250">
      </td>
      <td>
        <img align="center" src="./images/img3.png" width="250">
      </td>
      <td>
        <img align="center" src="./images/img4.png" width="250">
      </td>
      <td>
        <img align="center" src="./images/img5.png" width="250">
      </td>
    </tr>
  </tbody>
</table>
<br />

### ✔ 건강보험공단 경력 불러오기
> - 담당업무 : 편리한 이력서 등록을 위한 팝업창 구축 및 유지보수
> - 퍼블리싱 : 100%
> - 작업기간 : 2주
> - Skill : ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
<br />

###### 갼략 캡쳐본
<table>
  <tbody>
    <tr>
        <td>
          <img align="center" src="./images/img6.png" width="200">
        </td>
        <td>
          <img align="center" src="./images/img7.png" width="200">
        </td>
        <td>
          <img align="center" src="./images/img8.png" width="200">
        </td>
    </tr>
    <tr>
        <td>
          <img align="center" src="./images/img10.png" width="200">
        </td>
        <td>
          <img align="center" src="./images/img11.png" width="200">
        </td>
        <td>
          <img align="center" src="./images/img12.png" width="200">
        </td>
    </tr>
  </tbody>
</table>
<br />

# 🚀 Skills
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![css](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white) ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white) ![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) 
![Git](https://img.shields.io/badge/git-%23121011.svg?style=for-the-badge&logo=git&logoColor=white)
![VS Code Insiders](https://img.shields.io/badge/VS%20Code%20Insiders-35b393.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)

<br />
<br />

# 📞 Contact
- 이메일 : 1994being@naver.com
- 연락처 : 010.8820.9722
- 깃허브 : <a href="https://github.com/zziinnn">
  <img src="https://user-images.githubusercontent.com/68724828/185908612-22f4d219-78a7-4de7-bb02-deecaa63bffa.png" height="28px" style="margin-top: 10px" />
  </a>

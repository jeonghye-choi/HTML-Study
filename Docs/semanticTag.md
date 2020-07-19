# 📙 시맨틱 태그 (semantic tag)

참고: <a href="https://thrillfighter.tistory.com/492">https://thrillfighter.tistory.com/492</a>

### ✔ 중요성

1. 구조파악

2. 검색엔진 노출

: 검색엔진에 중요한 부분과 덜 중요한 부분을 파악할 수 있게 해주어 효과적인 검색을 하도록
도와준다

### ✔ 시맨틱 태그 레이아웃

![image](https://user-images.githubusercontent.com/54584063/87870353-23490000-c9e2-11ea-8d9d-7caec8692a5e.png)


|  <center>태그</center> |  <center>내용</center> |
|:--------:|:--------:|
| <center>\<header></center>| <center>머리글/ 로고/ 제목/ nav포함</center> |
| <center>\<nav></center>| <center>네비게이션 링크 모음/ 메뉴</center> |
| <center>\<section></center>| <center>컨텐츠 그룹핑/ 주제별 컨텐츠 영역</center> |
| <center>\<article></center>| <center>콘텐츠 실제 내용</center> |
| <center>\<aside></center>| <center>사이드바 영역(광고, 링크 등)</center> |
| <center>\<footer></center>| <center>하단(제작정보, 회사소개, 약관, 저작권 정보)</center> |

<br>

|  <center>태그</center> |  <center>내용</center> |
|:--------:|:--------:|
| <center>\<details></center>| <center>사용자가 보거나 숨길 수 있는 추가적인 세부 정보 정의</center> |
| <center>\<figcaption></center>| <center>figure에 대한 자막</center> |
| <center>\<figure></center>| <center>사진이나 다이어그램</center> |
| <center>\<main></center>| <center>문서의 주가 되는 컨텐츠</center> |
| <center>\<mark></center>| <center>참조, 하이라이트 표시</center> |
| <center>\<summary></center>| <center>detials에 대한 보이는 요소 정의</center> |
| <center>\<time></center>| <center></center> |


```html
<!DOCTYPE>
<html>
    <head>
        <meta charset="utf-8">
    </head>
    <body>
        <header>
            <h2>Jeonghye's Story</h2>
            <nav>
                <span> <a href="">코딩</a> </span>
                <span> <a href="">그림</a> </span>
                <span> <a href="">책</a> </span>
            </nav>
        </header>

        <section>
            <article>
                <h3>코딩</h3>
                <p>dflasdkjflkjweo;hgbkjfdnkad</p>
                <div>oioierkwejfhskjfd</div>
            </article>
            <article>
                <h3>그림</h3>
                <p>dflasdkjflkjweo;hgbkjfdnkad</p>
            </article>
            <article>
                <h3>책</h3>
                <p>dflasdkjflkjweo;hgbkjfdnkad</p>
            </article>
        </section>

        <aside>
            광고영역
        </aside>

        <footer>
            Copyright@ jeonghye
        </footer>
    </body>
</html>
```
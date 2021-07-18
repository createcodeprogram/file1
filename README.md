# file1
<html>
<head>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Zen+Loop&display=swap" rel="stylesheet">
  <style>
    html{color:red}
    /*border과 같은 선택자의 경우 상속이 안됨*/
    #blue{color:blue}
    h3{font-size:16px;}
    #rem{font-size:1rem;}
    h4{color:rgb(0,180,120);
       text-align:center;}
    #not{color:black;
         border: 1px solid skyblue;
         text-align:justify;}
    h6{color:rgb(0,200,200);
       font-size:1rem;
       font-family:cursive;
       font-weight:bold;
       line-height:2}
    h7{font-family:'Zen Loop', cursive; color:blue}
  </style>
</head>
<body>
<h2>수업내용</h2>
<ul>
<Li>Html</li>
<li id='blue'>Css</li>
<li>Java</li>
</ul>
<h3>Hello World</h3>
<h3 id='rem'>Using Rem<h3>
<!--color등과 같은 tag등이 중첩될 때 적용되는 순서(영향력power가 쎈 순위)
0. !important 추가(ex.li{color:red !important;})
1. style attribute(ex.li style='blue')
2. id selector
3. class selector
4. tag selector-->
<h4>Using Css</h4>
<p id='not'>종속형 시트 또는 캐스케이딩 스타일 시트(Cascading Style Sheets, CSS)는 마크업 언어가 실제 표시되는 방법을 기술하는 언어로,
  HTML과 XHTML에 주로 쓰이며, XML에서도 사용할 수 있다. W3C의 표준이며, 레이아웃과 스타일을 정의할 때의 자유도가 높다.
마크업 언어(ex: HTML)가 웹사이트의 몸체를 담당한다면 CSS는 옷과 액세서리처럼 꾸미는 역할을 담당한다고 할 수 있다.
즉, HTML 구조는 그대로 두고 CSS 파일만 변경해도 전혀 다른 웹사이트처럼 꾸밀 수 있다.</p>
<h6 id='type1'>Hello World<br>
  Hello World</h6>
<h7>CSS는 단순한 문법을 가지며, 수많은 영어 키워드를 사용하여 다양한 스타일의 프로퍼티의 이름을 규정한다.
스타일 시트는 규칙의 목록으로 구성된다. 각 규칙이나 규칙 집합은 하나 이상의 셀렉터와 하나의 선언 블록을 이룬다.
CSS는 따로 CSS만의 코드가 필요하지 않고, 그대로 HTML 문서에 CSS의 키워드를 넣으면 된다.</h7>
</body>
</html>

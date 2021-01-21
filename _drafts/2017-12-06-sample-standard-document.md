---
layout: standard
title: "표준 제목"
subtitle: "표준세트명"
categories: standard
---

<table class="invisibleTable">
<tbody>
<tr>
<td style="width: 143px; vertical-align: middle;" width="143"><img class="aligncenter wp-image-1247 size-full" src="{{ "/assets/images/imskorea_logo_1.png" | absolute_url }}" alt="imskorea_logo_1" width="143" height="39" /></td>
<td><span style="font-size: 20pt;"><strong>표준 제목</strong></span></td>
</tr>
</tbody>
</table>
<table class="invisibleTable">
<tbody>
<tr>
<td width="143"><strong>발행일</strong></td>
<td><strong>2017년 12월 1일</strong></td>
</tr>
<tr>
<td width="143"><strong>최신버전</strong></td>
<td>최신 버전 설명</td>
</tr>
<tr>
<td width="143"><strong>이전버전</strong></td>
<td>이전 버전 설명</td>
</tr>
</tbody>
</table>
<!-- toc -->
<div class="row">
  {% include toc.html html=page.content sanitize=true id="my_toc" class="caption" %}
</div>
<!-- toc -->
<h1><a name="introduction">1. 서론</a></h1>

내용

<h1><a name="body">2. 본론</a></h1>

내용

<b>굵은 글씨</b>
<i>기울임꼴</i>
<u>밑줄</u>

<h2><a name="quote">2.1. 인용문 넣기</a></h2>

> 줄 앞에 '>' 표시를 붙여서 작성하시면 됩니다. <br>
> 여러 줄에 걸쳐서 작성하는 경우, 각 줄 앞에 '>'를 붙여서 작성합니다. <br>
> 줄 바꾸기는 `<br>` 태그를 이용하세요.

<h2><a name="ol">2.2. 숫자가 있는 목록</a></h3>

1. 항목 1
2. 항목 2
3. 항목 3

<h2><a name="code">2.3. 코드/JSON 넣기</a></h3>

```
<html>
  <head>
  </head>
  <body>
    <p>Hello, World!</p>
  </body>
</html>
```

<h2><a name="table">2.4. 표 넣기</a></h3>

`<table>` 태그를 이용하거나, 다음과 같이 작성하세요.

| 표 윗부분 내용 | 표 윗부분 내용 |
|---------|--------|
| 칸의 내용 | 칸의 내용 |
| 칸의 내용 | 칸의 내용 |

<h2><a name="images">2.5. 그림 넣기</a></h3>

![그림 설명](https://www.google.co.kr/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)

<h2><a name="link">2.6. 링크 걸기</a></h3>

[Google](http://www.google.com)

<http://www.keris.or.kr>

<h1><a name="conclusion">3. 결론</a></h1>

내용

# learn-gfm

## GFM이란?

## Tables
- 테이블을 만들려면, 파이프(|)와 하이픈(-)을 사용한다.   
하이픈은 각 열의 헤더를 만드는데 사용되고, 하이플은 각 열은 구분한다.  

- 올바른 렌더링을 위해서는 테이블 앞에 빈 줄을 포함해야한다.

 - 셀은 너비가 다를 수 있으며 열 내에서 완벽하게 정렬될 필요는 없다. 하지만 헤더 행의 각 열에는 최소한 세 개의 하이픈은 있어야한다


**Markdown 예시** <br>
<p>
| First Header  | Second Header | <br>
| ------------- | ------------- | <br>
| Content Cell  | Content Cell  | <br>
| Content Cell  | Content Cell  | 
</p>

 <br>

**🌈결과 ⬇** <br>
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

 <br>


- 테이블 내에서 링크, 텍스트 스타일 등의 서식을 사용할 수 있다.


**Markdown 예시** <br>
<p>
| Command | Description | <br>
| --- | --- | <br>
| `git status` | List all *new or modified* files | <br>
| `git diff` | Show file differences that **haven't been** staged | <br> 
</p>

 <br>

**🌈결과 ⬇** <br>
 | Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |
 <br>

- 헤더 행의 하이픈의 왼쪽, 오른쪽 또는 양쪽에 콜론을 포함하여 텍스트를 열의 왼쪽, 오른쪽 또는 가운데로 정렬할 수 있다.

**Markdown 예시** <br>
<p>
| Left-aligned | Center-aligned | Right-aligned | <br>
| :---         |     :---:      |          ---: | <br>
| git status   | git status     | git status    | <br>
| git diff     | git diff       | git diff      | <br>
</p>

 <br>

**🌈결과 ⬇** <br>

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

 <br>

- 파이프를 셀의 컨텔츠로 사용하려면, 백슬래시(\)를 파이프 전에 사용한다.

**Markdown 예시** <br>
<p>
| Name     | Character | <br>
| ---      | ---       | <br>
| Backtick | `         | <br>
| Pipe     | \|        | <br>
</p>

 <br>

**🌈결과 ⬇** <br>

| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |

 <br>


## Task list items 
- 깃헙에서는 체크박스 리스크 기능을 추가로 사용할 수 있다.

**Markdown 예시** <br>
<p>
- [ ] foo
- [x] bar
</p>

**🌈결과 ⬇** <br>
<ul>
<li><input disabled="" type="checkbox"> foo</li>
<li><input checked="" disabled="" type="checkbox"> bar</li>
</ul>

<br>

## Strikethrough 
- 깃헙에서는 ~(물결) 기호를 사용해서 글자에 취소선을 그을 수 있다.

**Markdown 예시** <br>
<p>
지금은 ~~재밌게~~ 넷플릭스를 보는 중입니다.
</p>

 <br>

**🌈결과 ⬇** <br>
지금은 ~~재밌게~~ 넷플릭스를 보는 중입니다.

## Autolinks 
- 깃헙은 표준 URL에서 자동으로 링크를 생성한다. 

**Markdown 예시** <br>
<p>
Visit https://github.com
</p>

 <br>

**🌈결과 ⬇** <br>

Visit https://github.com

 <br>


## Disallowed Raw HTML 
- 깃헙은 tagfilter를 활성화하여, 다음의 HTML 태그들이 렌더링 될때 필터된다. 

\<title>,\<textarea>,\<style>,\<xmp>,\<iframe>,\<noembed>,\<noframes>,\<script>,\<plaintext>

- 필터링이 될때 위의 HTML 태그들의 <를 &lt;로 대체하여 수행한다. 

**Markdown 예시** <br>

\<strong> \<title> \<style> \<em>

\<blockquote>
  \<xmp> is disallowed.  \<XMP> is also disallowed.
\</blockquote>

 <br>

**🌈결과 ⬇** <br>

<p><strong> &lt;title> &lt;style> <em></p>
<blockquote>
  &lt;xmp> is disallowed.  &lt;XMP> is also disallowed.
</blockquote>

 <br>


### 출처
https://github.github.com/gfm/      
https://docs.github.com/en/github/writing-on-github/organizing-information-with-tables   
https://codelabs-markdown.web.app/

# Headings (제목)
- \#을 문장 앞에 붙이면 Heading을 사용할 수 있다. 앞에 붙이는 \#의 개수에 따라 Heading의 레벨이 달라진다.

- 예를 들어 html의 \<h2>를 사용하려면 문장 앞의 2개의 \#을 붙이면 된다. <br >

**Markdown 예시**
\# Heading level 1 <br />
**HTML:**
\<h1> Heading level 1<br />

**🌈결과 ⬇**
# Heading level 1
**Markdown:**
\## Heading level 2 <br />
**HTML:**
\<h2> Heading level 2 <br />

**🌈결과 ⬇**
## Heading level 2
<br >

- 문자 밑에 개수에 상관 없이 ==를 붙이면 heading level1, --를 붙이면 heading level2가 된다.<br><br>
Heading level 1 <br>
\======== <br>
Heading level 2 <br >
\-----
<br ><br>

- 제목과 \# 사이의 빈 공간이 없으면, 마크다운 언어는 인식하지 못하므로 주의하자.<br>
#인식 못함 <br>
\# 인식함

<br>

# Paragraphs (단락)

- 단락을 만들기 위해 빈 줄을 사용해서 하나 이상의 텍스트 줄을 구분해야한다.

**Markdown 예시** <br>
나는 마크다운을 사용하는 것을 좋아한다.

<br>

지금부터 나의 모든 문서들을 작성하는데 마크다운을 사용할 것이다.

<br>

**HTML** <br>
\<p>나는 마크다운을 사용하는 것을 좋아한다.\</p>

<br>

\<p>지금부터 나의 모든 문서들을 작성하는데 마크다운을 사용할 것이다.\</p>

<br>

**🌈결과 ⬇** <br>
나는 마크다운을 사용하는 것을 좋아한다.

지금부터 나의 모든 문서들을 작성하는데 마크다운을 사용할 것이다.

<br>


# Line Breaks (줄 바꿈)
- 줄 바꿈을 하려면, 줄 마지막에 두 개 이상의 공백과 함께 리턴(엔터)키를 눌러라.

**Markdown 예시** <br>
This is the first line.&nbsp;&nbsp;  
And this is the second line.

**HTML** <br>
\<p>This is the first line.\<br>
And this is the second line.\</p>


<br>

**🌈결과 ⬇** <br>
This is the first line.  
And this is the second line.

<br>

# Emphasis (강조)
- 마크다운을 사용하면 글자를 bold 또는 italic 만들어 강조할 수 있다.

## Bold
- 글자를 bold로 만들려면, 두 개의 별(*) 또는 두 개의 언더바(_)를 단어 또는 문장의 앞뒤로 추가하자.   

<br>

**Markdown 예시** <br>
I just love \_\_bold text__.   
I just love \*\*bold text**.

<br>


**HTML** <br>
I just love \<strong>bold text\</strong>.

<br>

**🌈결과 ⬇** <br>
I just love __bold text__.   

<br>

- 단어의 중간을 bold로 만들려면, 글자 앞 뒤로 두 개의 별(*)을 추가한다. 언더바(_)는 불가능하니 주의하자.

**Markdown 예시** <br>
um\*\*br**ella 

<br>

**🌈결과 ⬇** <br>
um**br**ella 

<br>

## Italic

- 글자를 italic으로 만들려면, 한 개의 별(*) 또는 한 개의 언더바(_)를 단어 또는 문장의 앞뒤로 추가하자.   

<br>

**Markdown 예시** <br>
I just love \_italic text_.   
I just love \*italic text*.

<br>

**HTML** <br>
I just love \<em>italic text\</em>.

<br>

**🌈결과 ⬇** <br>
I just love _italic text_.   

<br>

- 단어의 중간을 italic으로 만들려면, 글자 앞 뒤로 한 개의 언더바(_)를 추가한다. 별(*)은 불가능하니 주의하자.

**Markdown 예시** <br>
um\*\*br**ella 

<br>

**🌈결과 ⬇** <br>
um**br**ella 

<br>

# Blockquotes (인용)
- 인용문을 만들려면, 단락 앞에 \>를 추가하자.

**Markdown 예시** <br>
\> 나를 죽이지 못하는 고통은 나를 더 강하게 만든다.

<br>


**🌈결과 ⬇** <br>
> 나를 죽이지 못하는 고통은 나를 더 강하게 만든다.

<br>

- Blockquotes은 여러 개의 단락을 포함할 수 있다. 이를 위해 단락들 사이에 빈 줄들에 \>를 더한다.

**Markdown 예시** <br>
\> 나를 죽이지 못하는 고통은 나를 더 강하게 만든다.   
\>   
\> 아무것도 성취하지 못했을지라도 자신을 존경하라. 거기에 상황을 바꿀 힘이 있으니. 

<br>


**🌈결과 ⬇** <br>
> 나를 죽이지 못하는 고통은 나를 더 강하게 만든다.   
>
> 아무것도 성취하지 못했을지라도 자신을 존경하라. 거기에 상황을 바꿀 힘이 있으니. 

<br>

- 중첩된 인용문을 사용하려면, 중첩을 원하는 단락에 \>\>을 더하자.

**Markdown 예시** <br>
\> 나를 죽이지 못하는 고통은 나를 더 강하게 만든다.   
\>   
\>> 아무것도 성취하지 못했을지라도 자신을 존경하라. 거기에 상황을 바꿀 힘이 있으니. 

<br>


**🌈결과 ⬇** <br>
> 나를 죽이지 못하는 고통은 나를 더 강하게 만든다.   
>
>> 아무것도 성취하지 못했을지라도 자신을 존경하라. 거기에 상황을 바꿀 힘이 있으니. 

- 인용문은 다른 마크다운 포맷의 원소들을 포함할 수 있다.

**Markdown 예시** <br>
\> ### 나를 죽이지 못하는 고통은 나를 더 강하게 만든다.   
\>   
\> - 아무것도 성취하지 못했을지라도 자신을 존경하라.       
\> - 거기에 상황을 바꿀 힘이 있으니. 

<br>


**🌈결과 ⬇** <br>
> ### 나를 죽이지 못하는 고통은 나를 더 강하게 만든다.   
>   
> - 아무것도 성취하지 못했을지라도 자신을 존경하라.       
> - 거기에 상황을 바꿀 힘이 있으니. 


# Lists (목록)
- 마크다운으로 항목들을 정렬된 또는 정렬되지 않은 상태로 구성할 수 있다.

## 정렬된 목록
-  항목 앞에 숫자 다음 마침표(.)를 찍는다. 적힌 숫자랑 상관없이 순서대로 번호가 매겨진다. 하지만 목록은 숫자 1로 시작해야한다.

**Markdown 예시** <br>
1. First item
2. Second item
3. Third item

**HTML** <br>
\<ol>
\<li>First item<\/li>
\<li>Second item\</li>
\<li>Third item\</li>
\</ol>	

**🌈결과 ⬇** <br>
1. First item
2. Second item
3. Third item

<br>

**Markdown 예시** <br>
1. First item
2. Second item
    1. Indented item
    2. Indented item
3. Third item

**🌈결과 ⬇** <br>
1. First item
2. Second item
    1. Indented item
    2. Indented item
3. Third item

<br>

## 정렬되지 않은 목록
- 항목 앞에  - 또는 * 또는 +를 더한다.    
셋 중 무엇을 사용해도 좋으나 서로 다른 문자를 섞어서 사용하면 안된다.

**Markdown 예시** <br>
\- First item   
\- Second item

**HTML** <br>
\<ul>
\<li>First item\</li>
\<li>Second item\</li>
\</ul>

**🌈결과 ⬇** <br>
- First item
- Second item

<br>

# Horizontal Rules (수평선)
- 수평선을 만들려면 세 개의 별(***), 세 개의 대쉬(---) 또는 세 개
의 언더바(___)를 한 줄에 단독으로 작성한다. 

**Markdown 예시** <br>
\***   
\---   
\___   

<br>

**🌈결과 ⬇** <br>
***
---
___

<br>

- 호환성을 위해 수평선 앞뒤에 빈 줄을 둬야한다.   

**Markdown 예시** <br>

앞 뒤로 빈 줄이 없으면,    
\---   
제목이 된다.   


**🌈결과 ⬇** <br>

앞 뒤로 빈 줄이 없으면, 
---   
제목이 된다.   

<br>

**Markdown 예시** <br>

앞 뒤로 빈 줄이 있으면,   
        
\---   

수평선이 된다.   

**🌈결과 ⬇** <br>

앞 뒤로 빈 줄이 있으면,   
        
---   

수평선이 된다.  

<br>

# Links
- 링크를 만들려면 링크 제목을 대괄호[]에 입력하고, URL을 소괄호()에 입력한다.

**Markdown 예시** <br>
\[마크다운 가이드]\(https://www.markdownguide.org/)

**🌈결과 ⬇** <br>
[마크다운 가이드](https://www.markdownguide.org/)

<br>

- URL 뒤 소괄호 내부에 설명을 추가하면, 사용자가 링크 위로 마우스를 가져갔을 때 링크 설명을 볼 수 있다.   
   
<br>

**Markdown 예시** <br>
My favorite search engine is \[Duck Duck Go]\(https://duckduckgo.com "The best search engine for privacy").

**🌈결과 ⬇** <br>
 
 My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

<br>

- 꺽쇠 괄호<>를 통해 URL 또는 이메일 주소를 빠르게 링크로 변환할 수 있다.

<br>

**Markdown 예시** <br>
\<https://www.markdownguide.org>

\<fake@example.com> 

**🌈결과 ⬇** <br>
 
<https://www.markdownguide.org>
<fake@example.com>

<br>

# Images

- 이미지를 추가하려면 느낌표(!)와 뒤따라오는 대괄호 안의 대체 텍스트, 소괄호 안의 이미지 경로 또는 URL을 작성한다.   

<br>

**Markdown 예시** <br>
<p>![마크다운](https://user-images.githubusercontent.com/40673012/112839492-3c5d9100-90d9-11eb-9ec0-bccf9fcaa13c.png "이것은 마크다운 이미지입니다.")
</p>

**🌈결과 ⬇** <br>
 
![마크다운](https://user-images.githubusercontent.com/40673012/112839492-3c5d9100-90d9-11eb-9ec0-bccf9fcaa13c.png "이것은 마크다운 이미지입니다.")

<br>

# Escaping Characters

- 마크다운 문서에서 텍스트 서식을 지정하는 데 사용되는 리터럴 문자를 표시하려면 문자 앞에 백 슬래시(\)를 추가한다. <br>  
예를 들어 다음과 같이 문자에 볼드체를 사용한 경우 *bold* <br>
사용한 리터럴 문자 앞에 백 슬래시를 추가하면 \*bold\* 가 된다. 

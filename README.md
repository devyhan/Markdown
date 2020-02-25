# 1.마크다운(Markdown)🏁

## 1.1.마크다운 이란 ? 

[**Markdown**](http://whatismarkdown.com/)은 텍스트 기반의 마크업언어로 2004년 존그루버에 의해 만들어졌으며 쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능하다. 특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여 웹에서도 보다 빠르게 컨텐츠를 작성하고 보다 직관적으로 인식할 수 있다.

# 2.공통 마크다운 문법(Global Syntex)🏝

## 2.1.헤더(Header)
    # This is an H1 tag
    ## This is an H2 tag
    ### This is an H3 tag
    #### This is an H4 tag 
    ##### This is an H5 tag
    ###### This is an H6 tag
### 적용 예
****    
# This is an H1 tag
## This is an H2 tag
### This is an H3 tag
#### This is an H4 tag 
##### This is an H5 tag
###### This is an H6 tag
****
## 2.2.(Emphasis)
    *This text will be italic*
    _This will also be italic_

    **This text will be bold**
    __This will also be bold__

    _You **can** combine them_
### 적용 예
****
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
****
## 2.3.리스트(List)
### 2.3.1.Unordered 리스트
    * Item 1
        * Item 2
        * Item 2a
        * Item 2b
 ### 적용 예
 ****
 * Item 1
    * Item 2
    * Item 2a
    * Item 2b
 ****
 ### 2.3.2.Ordered 리스트
    1. Item 1
    1. Item 2
    1. Item 3
       1. Item 3a
       1. Item 3b
 ### 적용 예
 ****
 1. Item 1
 1. Item 2
 1. Item 3
    1. Item 3a
    1. Item 3b
 ****
## 2.4.이미지(Images)
    ![GitHub Logo](이미지 Url)
    Format: ![Alt Text](이미지 url)
****
<img src="https://user-images.githubusercontent.com/45344633/75291822-54276d80-5866-11ea-94dd-2ab210ee2766.png" width="400px" height="100px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>
****
## 2.5.링크(Links)
    http://github.com - automatic!
    [GitHub](http://github.com)
### 적용 예
****
http://github.com - automatic!
[GitHub](http://github.com)
****
## 2.6.인용부호(Blockquotes)
    As Kanye West said:

    > We're living the future so
    > the present is our past.
### 적용 예
****
As Kanye West said:

> We're living the future so
> the present is our past.
****
## 2.6.인라인 코드(Inline code)
    <addr>에 적용된 부분이
    `<addr>` 인라인 코드 입니다.
### 적용 예
****
\<addr\>에 적용된 부분이
`<addr>` 인라인 코드 입니다.
****

# 3.깃헙 마크다운 문법(Local Syntex)🏖

## 3.1.구문 강조(Syntax highlighting)
    ```javascript
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    ```
### 적용 예
****
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
****


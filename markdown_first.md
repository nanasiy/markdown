# Markdown

일반 데티스 형식 구문을 사용하는 마크업 언어의 일종인 마크다운은 사용법이 참 쉽고 간결합니다.
따라서 빠르게 문서 정리를 할 수강 있지요.
단!! 모든HTML 마크업을 대체하지는 않습니다.

HTML Markup(마크업) <-> Markdown(마크다운)

* 마크업 : 문서에서 특정 내용이 어떤 역할을 하는지 표시
* 마크다운: 번거로운 마크업의 태그를 더 간단한 기호로 표시

## 문법
### 1.1 Header
> 헤더는 제목을 표현할때 사용.
> 단순히 글자 크기가 아니다.
> 의미적인 중요도!

# h1태그
## h2태그
### h3태그
#### h4태그
##### h5태그
###### h6태그

### 1.2 List
> 목록 나열에 사용
* 순서가 있는 목록
1. 순서가 있는 상위 항목
2. 순서가 있는 상위 항목
    1. 순서가 있는 하위 항목
    2. 순서가 있는 하위 항목
        1.순서가 있는 하하위 항목
        
* 순서가 없는 목록
* 순서가 없는 상위 항목
    * 순서가 없는 하위 항목
        * 순서가 없는 하하위 항목

### 1.3 Code Block
> 코드 블럭은 작성한 코드를 정리, 강조할 때 사용
> 이것도 인라인과 블럭으로 나눠서 사용 강조

* inline : 택빅을 이용해 사용
    `console.log('hellow');`
* block : 백틱을 세 번 이용해 사용
    ```javascript
    console.log('hellow');
    ```
    
### 1.4 Image
> 로컬 이미지 삽입 또는 링크 활용해 삽입 가능

* `![]()`로 작성 `()`안에 이미지 주소

![](data:image/png;base64,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) 

### 1.6 Table 
> 표를 작성
* `|` 파이프 사이에 컬럼

|이름|학과|먹고 싶은 과자|
|김민재|컴퓨터|세우깡|

### 1.7 기타

인용문 : `>`

수평선 : `---`

강조 : `*이탤릭*`, `**볼드**`, `~~취소~~`


---
layout: post
title: 직접 사용할 마크다운 정리
subtitle: Markdown Basic
categories: markdown
tags: [markdown]
---

## 마크다운(Markdown) 문법 기초

1. 헤더(Headers)  
단락의 제목을 나타내며, 크기는 H1 > H2 > H3 > H4 > H5 > H6 순이다. 
# # H1
## ## H2
*H1과 H2는 선이 생긴다.*
### ### H3
#### #### H4
##### ##### H5
###### ###### H6

2. 강조(Emphasis)
    1. *이탤릭체* : `*ABC*` 또는 `_ABC_`  
    2. **볼드체** : `**ABC**` 또는 `__ABC__` 

3. 취소선 (Strikethrough)
    `---`
    ---

4. 개행 (New Line)
    1. 문장 끝에 공백 두 개(&nbsp;&nbsp;)와 Enter 추가 한 번 개행한 뒤 작성  
        `Hello `&nbsp;`(enter)'`world
    2. 개행하고 싶은 문장 사이에 개행(Enter)을 두 번 입력  
        Hello<br>World
    3. `<br>`을 문장 뒤에 추가한다.  
        `Hello<br>world`
    
5. 인라인 코드(Inline Code) : 백틱(\`)으로 감싼다.

    자료구조 정수형 중 하나인 Int의 Kotlin에서는 \``val a = 1`\`과 같이 선언할 수 있다.

6. 코드 블록 (Code Block) : 백틱 3개 (\'\'\')로 감싼다.  

    \`\`\`kotlin
    ```kotlin
    fun main() {
        println("Hello World!!!")
    }
    ```
    \`\`\`

7. 링크 (Links)  
    `[Google](http://www.google.com)` -> [Google](http://www.google.com)

8. 인용문 (Blockquotes)
    > '직접 인용' : 원문을 그대로 가져다 쓰는 행위  
    > '간접 인용' : 원문과 내용을 정리하여 자신의 언어로 풀어 쓴 것
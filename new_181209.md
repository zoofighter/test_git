## markdown 이란

> Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML)

** 즉, 마크다운은 다음과 같은 성질을 가지는 텍스트를 HTML로 변환하는 언어이자 도구이다 **
1. 사람이 읽고 쓰기 쉽다.
2. 컴퓨터도 이해하기 쉽다.

마크다운은 간단한 문법만을 사용해 글을 구조적으로 작성할 수 있고, 마크다운으로 작성된 글을 그냥 읽어도 이해하기 쉽고 HTML로 변환해도 보기에 좋다. 이 때문에 최근 GitHub 같은 개발 관련 웹사이트에서 마크다운을 많이 사용하고 있다

## 마크업 언어

HTML은 Tag 를 이용하여 자료의 구조를 만드는 대표적인 마크업 언어입니다.  
마크업 언어는 문서에 포함된 내용에 대한  ~~정보가 아니라~~, 글자의 크기나 형태, 그래픽, 여백 등
문서가 화면에 표시되는 형식을 정의하는데 필요한 언어입니다.  
HTML / CSS / Javascript / jQuery는 클라이언트 측 언어로,클라이언트 측에서 실행되고,  실행 결과를 웹 브라우저를 통해 화면에 보여 줍니다
CSS는 HTML로 뼈대를 잡은 웹 페이지를 꾸며주는 역할을 합니다.

*참조사이트 *  
[마크다운 사용법1](http://danielku.com/posts/2014-02-13-markdown/)  
[마크다운 사용법2](https://heropy.blog/2017/09/30/markdown/)  
[마크다운 사용법3](http://blog.hyeyoonjung.com/2017/05/30/how-to-use-markdown/)  
[마크업](https://blog.naver.com/green_0807/221343206511)

## markdown 간단사용법(명령어 10개)`

1. code block '''python '''   문장 내에서도 `코드` 삽입이 가능하다.
2. table
3. subject #, ##
4. list_item  (*,-, number).
5. [https](https://google.com)
***

6. black qouete ^  인용문
7. -italic-  
8. **bold**
9. ~~cancel
10. /hr   * * *
****

## number 2 table

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |

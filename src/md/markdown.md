# 마크다운 문법

## 헤더 문법

- `#` 문서의 제목이나 섹션의 소제목을 만드는 문법으로 `#`이 붙을수록 헤더의 스케일이 작아짐. 1~6의 범위를 가짐.
  **이하 예시**

---

# H1 `#=H1`

## H2 `##=H2`

### H3 `###=H3`

#### H4 `####=H4`

##### H5 `#####=H5`

###### H6 `######=H6`

---

## 강조문법

- 문서의 내용을 강조하고 보조적인 의미를 주는 문법
  **이하 예시**

---

**굵게** `**<텍스트>**` `__<텍스트>__`
_기울임_ `*<텍스트>*` `_<텍스트>_`
~~취소선~~ `~~<텍스트>~~`

---

## 수평선

- 문서에서 표현의 필요성에 따라 수평선을 긋는 문법 `- , * , _`을 3번이상 연속하여 작성해서 사용. **`-`**를 사용할 경우 헤더로 인식할 수 있으므로 전 라인은 비워둬야 함.
  **이하 예시**

---

--- `---`

## 목록 만들기

- 순서 있는 목록 : 줄의 가장 앞에 숫자와 온점을 (`1.`) 기입하면 순서가 있는 목록이 됨. 순서대로 1부터 목록을 매김
- 순서 없는 목록 : `*, -, _`를 입력하면 순서가 없는 목록이 됨
  **이하 예시**

---

1. 일 `1.`
2. 이 `2.`
3. 사 `4.` (코드 상으로 `1과 2 다음에 4.`를 기입해도 순서대로 3.으로 출력됨을 확인.)

- 순서 `-`
- 없는 `-`
- 목록 `-`

---

## 인용

- 줄의 가장 앞에 `>`를 기입해 만드는 문법으로 내가 하지 않은 다른 사람의 말 처럼 본문에 나와있지 않은 어떤 정보를 전달하는데 쓰임
- `>`의 숫자로 인용문의 들여쓰기 위치가 달라지고, 3개까지 가능
  **이하 예시**

---

저는 밥 아저씨께서 생전에 이런 말씀을 하시는 것을 들어 보았습니다

> 참 `>`

> > 쉽 `>>`

> > > 죠? `>>>`

---

## 링크

- 이미지링크 : 이미지를 불러오는 문법 `![대체문구](이미지 경로)` 여기서 이미지 경로는 로컬과 외부(url)링크 방식이 모두 가능. 대체문구는 마우스오버를 하거나, 화면의 정보를 음성으로 읽어주는 프로그램이 인식해 읽을 때 각각 텍스트와 음성으로 출력되는 내용.
- 파일이나 주소 링크 : `[문서의 텍스트](내부경로 or 외부 url)` 경로의 md파일을 불러오거나 웹사이트를 출력하는 명령어.
- 내부해시 링크 : 문서의 텍스트와 문서내부의 헤더를 연결하는 문법`[문서의 텍스트](이동할 헤드와 제목)`
  **이하 예시**

---

- ![이미지링크](../assets/ssam.jpg) `![이미지링크](../assets/ssam.jpg)` 이미지 링크
- [1주차회고](../md/week1-retrospect.md) `[1주차회고](../md/week1-retrospect.md)`
- [## 링크](#링크) `[## 링크](#링크)`

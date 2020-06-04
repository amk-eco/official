# AI Makers Kit(AI Coding Pack) 3rd Party 공식 개발 사이트

## 1. 개발 절차
#### Step.1 지니블록과 연동하려는 Robot을 제어하는 API 대한 기능 정의

- 지니블럭 서버에서 AMK Client로 전달해 주기 위해 규격 정의(아래의 형식의 엑셀파일로 전달 시, 구글 DOC Sheet 공유 페이지 생성)

#### Step.2 블럭 디자인 샘플

#### Step.3 AMK 단말 Client 개발(BlcokDriver.js)
- 자사에 로봇에서 활용하는 API에 대해 AMK 단말 내의 Python3 언어로 Call 할 수 있는 라이브러리 개발
- 지니블럭 서버와 통신을 위해 [Step1] 정의한 엑셀 파일의 내용대로 AMK Client의 nodejs에서 개발된 BlcokDriver에서 추가 구현

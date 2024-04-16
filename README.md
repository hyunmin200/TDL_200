# TDL_200

> 이 프로젝트는 React 중급 스터디에서 공부하면서 만든 미니 프로젝트입니다.

## ✅투두 리스트✅

간단하게 투두를 적을 수 있는 투두 리스트 사이트입니다.

## ⚙️사용 기술⚙️
react, ts, recoil, styled-components

## ℹ️설명
<img style="width: 400px" src="https://github.com/hyunmin200/TDL_200/assets/102218665/c826f871-63ed-4bdf-a795-0acd2bebaa99" />  

투두 리스트는 하나의 페이지로 이루어져 있습니다.  
Input구역에 원하는 텍스트를 입력하여 List에 등록할 수 있습니다.

### 카테고리 기능
<img style="width: 400px" src="https://github.com/hyunmin200/TDL_200/assets/102218665/da6f38d8-550c-4ec0-b634-40fa8d62ecae" />  

텍스트를 카테고리별로 구분이 가능합니다.  
기본값은 TO_DO이고 DOING, DONE등의 카테고리가 존재합니다.

또한 텍스트를 카테고리별로 분류해서 보여줍니다.  

<img style="width: 400px" src="https://github.com/hyunmin200/TDL_200/assets/102218665/af2a86a9-d3f1-4b23-9def-c9f1910cb717" />  
<br />
<img style="width: 400px" src="https://github.com/hyunmin200/TDL_200/assets/102218665/8e0162dc-686d-40c6-a290-259628326015" />  
<br />
<img style="width: 400px" src="https://github.com/hyunmin200/TDL_200/assets/102218665/78a2d4f6-877b-415b-a371-10f15d1a848c" />

### 버튼
Input구역에 텍스트를 작성하여 추가를 한고 리스트를 보면 버튼이 3가지가 존재합니다.

<img style="width: 400px" src="https://github.com/hyunmin200/TDL_200/assets/102218665/284e7155-e3f7-40e7-98fe-c96e790591ed" />

버튼은 현재 카테고리 제외 두 가지 변경 버튼과 삭제 버튼으로 구성이 되어있습니다.  
위 사진에서 DOING이나 DONE을 누르게 되면 현재 카테고리 영역에서 사라지고 DOING이나 DONE 카테고리 영역으로 갑니다.

삭제 버튼을 누르게 되면 리스트에서 삭제가 됩니다.

## 🧐느낀 점🧐
이번에 상태 관리 라이브러리인 recoil을 주로 사용하여서 ToDoList를 만들어보았습니다.
ToDoList를 만들면서 recoil의 다른 atom을 가져와 아웃풋을 변형시켜서 리턴하는 selector라는 기능을 처음으로 사용해보아서 좋았습니다.
또한, react와 styled-component, ts등도 사용해보면서 익숙해진 것 같습니다.


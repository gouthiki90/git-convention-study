# Git Commit Message Convention 사용해보기

## 기본적인 양식
```
<type>[optional scope]: <description>
[optional body]
[optional footer(s)]
```

```<type>```은 변경 사항 중 유형을 나타낸다.
- features / feat : 새로운 기능
- fix : 버그 수정
- docs : 문서 수정
- style : 스타일 수정
- refector : 코드 리펙토링
- test : 테스트 코드 수정
- chore: 기타 작업


```<description>```은 변경 작업의 제목이나 내용이다. 마침표를 사용하지 않으며 50자 내외로 작성하는 것이 좋다.
```<body>```는 작업 내용이 복잡하거나 상세한 내용을 남길 때만 작성하며 한 줄당 72자 내외로 작성하는 것이 좋다.
```<footer>```는 코드 작업과 관련하여 이슈 번호 또는 참조 링크 등을 추가한다. 해결한 경우에는 일반적으로 ```Closes #작업 또는 이슈 번호```로 작성한다.


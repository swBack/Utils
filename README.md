# Utils
# 수정/변경 사항
* 기존 IPRONWebCall.a, IPRONWebCall.h 변경
* IPRONWebCall_OptionValues.h 추가
* URL 변경
```
 [[IPRONWebCall alloc]initWithURL:url];
```
### 위 기존 url 값 변경 전
``` 
 [[IPRONWebCall alloc]initWithURL: "도메인/WebCallAPI/~"];
```

### 위 기존 url 값 변경 후
``` 
 [[IPRONWebCall alloc]initWithURL: "도메인/WebCallAPI_WK/~"];
```

#1 
해당 새 경로는 개발 중계 서버만 적용된 경로이며, 운영 서버에는 아직 적용되지 않았습니다.
테스트 확인 후 문제가 없을 경우 운영 서버에 패치 요청 예정입니다.

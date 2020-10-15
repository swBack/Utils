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

 

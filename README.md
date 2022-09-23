# SpringBoot-React-Study

# React 설정
> vscode 설치
> node.js 설치 (nmp 설치 됨)
> npm create-react-app board-app == 리액트 설치 및 board-app 폴더를 생성 <br>
> bootstrap 설치 == npm install bootstrap --save <br>
> axios 설치 == npm install axios --save <br>
> 리액트 라우터 설치 == npm install react-router-dom --save <br>
> 기타 등등 설치

# Spring boot 설정
> gradle <br>
> java version : 11 <br>
> jar <br>
> dependency : ~


# 연동시 CORS 문제 
> Spring boot 에서 @CrossOrigin 애노테이션을 사용하여 문제를 해결  <br>

``` java
@CrossOrigin(origins = "http://localhost:10001")
```

# FileUpload 문제
``` java
return axios({
         url: PRODUCT_BASE_REST_API_URL,
         method: 'post',
         data: product,
         headers: {
         'content-type': 'multipart/form-data'
         }
})
```

# 완전히 가운데로 사진 정렬 시키기
``` css
.target{
         position: absolute;
         top: 50%;
         left: 50%;
         /*완전 가운데로 주는 방법 translate 사용*/
         transform: translate(-50%, -50%);
}
```

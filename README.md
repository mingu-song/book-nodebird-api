## Node.js 교과서

* jwt 를 이용한 token 발행
* 사용량 제한을 위해 `npm i express-rate-limit` 사용
* api 버전업을 위해 하위 버전에 대해서 `router.use(deprecated);` 를 가장먼저 적용하여 응답회신
* cors 문제를 위해 `npm i cors` 사용
  * cors를 허용하여 중요한 정보가 노출된다면, 요청의 origin 값으로 도메인을 체크하는 이중보안 적용
    


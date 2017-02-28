# Cloud foundry deploy test app

#### 배포방법

```
	1. demo-0.0.1-SNAPSHOT.war 파일을 만들어준다.
	2. CF CLI 로그인후 앱을 배포하고 싶은 스페이스로 들어간다.
	3. cf push -f ./manifest.yml -m 512M -k 512M <= 명령어를 실행한다.
		실행하면 manifest.yml > name 으로 앱이 만들어집니다.
```
# ==끝!==
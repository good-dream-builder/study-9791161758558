
스프링으로 하는 마이크로서비스 구축 실습 2E

API 테스트시 인증(Client Credentials)
```shell
curl -k https://writer:secret@localhost:8443/oauth2/token -d grant_type=client_credentials -s
```
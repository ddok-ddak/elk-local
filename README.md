# 로컬에서 ELK 구성해보기
- 실상 : 로컬에서 대애충 elk 로깅이 어떤지 보자~
- 참고 레포 : https://github.com/deviantony/docker-elk
  - 위 레포를 참고 및 최대한 간소화하여 도커 컴포즈 구성
  
### 실행해보기
```bash
docker-compose -f ./docker-compose-elk-local.yml up -d
```

### 종료하기
```bash
docker-compose -f ./docker-compose-elk-local.yml down
# 해당 명령어 사용시 네트워크 및 컨테이너도 제거됨
```
  
### logstash
#### 참고
- 공식 레포 : https://github.com/elastic/logstash/tree/main/docker/data/logstash

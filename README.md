# hwanjin-linux_hyperledger

  <네트워크 작성하기>


 1. 준비물 생성 하기
 
 -crypto-config,yaml
 -configtx.yaml
 -generate.sh
 

 2. 네트워크 수행 하기
 
 -docker-compose.yaml
 -start.sh
 
 
 3. 채널 생성,조인 하기
 
 -start.sh
 -peer channel create
 -peer channel join
 
   <실습>
   
-cd
-mkdir my-network
-cd my-network
-mkdir application network contract
-cd~/fabric-samples/basic-network
-cp.env crypto-config.yaml configtx.yaml generate.sh
docker-compose.yml start.sh teardown.sh~/dev/my-network/network/

  <디렉토리 구성>
  
-cd network
-rm -rf crypto-config
-rm -rf config/*
-echo compose_project_name=net>.env
 
 

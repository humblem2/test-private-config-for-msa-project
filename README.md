# test-private-config-for-msa-project
test-private-config-for-msa-project

This is description of spring-cloud-config-repository 
for MSA Projects 
named by spring-cloud-zuul-config-eureka-merge-test.

Springboot Applciation:
- Using Embeded WAS and Build/Package/run jar

Run Configuration Enviroments:
- Local Develop: dev
- AWS Server Develop: beta
- AWS Server Product: real

Services(5EA):
- API Gateway Proxy Server(Edge server;Zuul Server) - Routing(Proxying) and L4 Loadbalancing(RR)
- Config Server(Config server)
- Dicovery and Register Server(Eureka Server)
- Normal Server(Frontend Server:port01/Frontend Server:port02)
- Data Access Server(Backend Server with Swagger) connected RDB(mysql) using mapper(Mybatis)



- From Config Remote Repository(https://github.com/humblem2/test-config)
# eureka
eureka注册中心demo
> eureka 多注册中心，互相注册
application-eureka1.properties
application-eureka2.properties
application-eureka3.properties
# 需要注意的是配置文件中的下述2行设置
> eureka.client.register-with-eureka=false（注册中心是否将自己注册）
  eureka.client.fetch-registry=false（是否获取注册服务）

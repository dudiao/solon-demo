
# 编译

## native
```shell
sdk use java 22.3.r17-grl

mvn clean native:compile -P tencentyun,\!77hub,native

./target/solon-demo 
```
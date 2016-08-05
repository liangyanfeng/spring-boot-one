# spring-boot-one

Source code for the blog: http://blog.callistaenterprise.se/2014/04/15/a-first-look-at-spring-boot/

maven 

默认最大线程数： 200

适当增加线程数， 会提高QPS

curl -i "http://localhost:8080/process?minMs=1000&maxMs=2000"

curl -i -H "accept:application/xml" "http://localhost:8080/process?minMs=1000&maxMs=2000"

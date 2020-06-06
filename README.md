# First-kube
kubernetes权威指南第二版1.3例子中的四个yaml文件
相较于原文修改的两个地方：  
1.其中mysql-rc.yaml里面的image需要改成mysql:5.7  
否则会出现Error:com.mysql.jdbc.exceptions.jdbc4.MySQLNonTransientConnectionException: Could not create connect  
2.myweb-rc.yaml中的replicas数目也减少到1个。在mac下的minikube集群中，replicas个数太多会导致apiserver出现异常  

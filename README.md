# Jenkins-Sonarqube-Maven-

描述：
windows环境下 Jenkins+Sonarqube+Maven+SVN/Git 图文搭建指南

版本：
Jenkins2.168
Sonarqube7.6
Maven3.6

说明：
个人从0搭建Jenkins+Sonarqube+Maven持续集成平台时临时做的图文资料，希望能帮助到有需要的人。
第一次搭建，不免有些地方没有深入理解，欢迎大神指正。

存在问题：
在Jenkins自动编译，调用Sonarqube插件校验代码过程中，无法做到多语言（java/js/web）同时校验。
对Sonarqube配置文件理解不通透，后续会逐步完善。暂时采用编译后，执行bat脚本，通过maven命令进行多语言校验。

更新方向：
1，会尝试使用Jenkins的Sonarqube插件，代替bat脚本，进行多语言的校验。

2，集成jacoco生成覆盖率测试报告


# Jenkins

**Plugins:**
* Pipeline stage view //to view the stages in pipeline
* AnsiColor  //for colours
* Pipeline Utility Steps  //to read Json
* Nexus Artifact Uploader   //for nexus
* Rebuild
*sonarqube scanner   //for sonarqube

Restart Jenkins once plugins are installed

Configure aws credentials in jenkins agent. you should configure with normal user.

disable node monitoring since our instances are with less memory. add jenkins agent as node inside jenkins master.
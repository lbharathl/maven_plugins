# maven_plugins

execute java plugins with command => mvn exec:java

executing webapp-tomcatdeployment with commands==> mvn tomcat7:deploy
                                                    mvn tomcat7:redeploy
                                                    mvn tomcat7:undeploy
                                                    
Executing build profiles commands==> mvn tomcat7:deploy -P DEV or QA                                                    
                                     mvn tomcat7:redeploy QA

# demoproject-thirdparty
Maven project to build and install third party dependency as OSGi bundle using maven-bundle-plugin and sling-maven-plugin respectively. (For use in AEM)

Export-Package entry is framed such that it includes all mentioned dependencies (as available in "dependencies" entry) via "*" with exclusions preceding before the same. 
Exclusion List are the ones that are already available in the AEM instance as OOTB bundles and is framed manually by checking in the local AEM instance. 
  
Classic AEM Version 6.5.0

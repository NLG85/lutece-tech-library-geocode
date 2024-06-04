![](https://dev.lutece.paris.fr/jenkins/buildStatus/icon?job=tech-library-geocodes-deploy)
[![Alerte](https://dev.lutece.paris.fr/sonar/api/project_badges/measure?project=fr.paris.lutece.plugins%3Alibrary-geocodes&metric=alert_status)](https://dev.lutece.paris.fr/sonar/dashboard?id=fr.paris.lutece.plugins%3Alibrary-geocodes)
[![Line of code](https://dev.lutece.paris.fr/sonar/api/project_badges/measure?project=fr.paris.lutece.plugins%3Alibrary-geocodes&metric=ncloc)](https://dev.lutece.paris.fr/sonar/dashboard?id=fr.paris.lutece.plugins%3Alibrary-geocodes)
[![Coverage](https://dev.lutece.paris.fr/sonar/api/project_badges/measure?project=fr.paris.lutece.plugins%3Alibrary-geocodes&metric=coverage)](https://dev.lutece.paris.fr/sonar/dashboard?id=fr.paris.lutece.plugins%3Alibrary-geocodes)

# Plugin library-geocodes

## Introduction

The purpose of this library is to provide a service to call the plugin geocode

## Configuration

For the configuration, in the context.xml file, it is necessary ton inject the httpTransport bean. You have also to fill the properties : APIM gateway url, AM token url, and credentials unless you use a direct access.There is also a mock that can be used for test. An example can be found in the context file of the plugin geocodesclient :https://github.com/lutece-platform/lutece-tech-plugin-geocodesclient/blob/master/webapp/WEB-INF/conf/plugins/geocodesclient_context.xml

Warning, the version 1.0.1 and before of the library use the date format yyyy-MM-DD and the V1 api of the plugin geocode which also use this date format. From version 1.0.2, the date format is yyyy-MM-dd and the api version of the plugin geocodes is V2.

## Usage

The local service GeoCodeService can be used to request on the cities and countries


[Maven documentation and reports](https://dev.lutece.paris.fr/plugins/library-geocodes/)



 *generated by [xdoc2md](https://github.com/lutece-platform/tools-maven-xdoc2md-plugin) - do not edit directly.*
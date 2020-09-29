# Using Gatling to generate load against Petclinic

_This assumes you have stood up PetClinic as per these instructions: [Instrumenting PetClinic](https://github.com/asantonio/petclinic-sfx)_


Step 1: Download Gatling into the working directory

Find the most recent version as per this "click here" link on this page: [gatling.io](https://gatling.io/open-source/start-testing/). For example:

```
$ curl -O https://repo1.maven.org/maven2/io/gatling/highcharts/gatling-charts-highcharts-bundle/3.3.1/gatling-charts-highcharts-bundle-3.3.1-bundle.zip
```

Unzip the file that was just downloaded
```
$ tar -xvf gatling-charts-highcharts-bundle-3.3.1-bundle.zip
$ cd gatling-charts-highcharts-bundle-3.3.1
```

# payarahello
This is a "hello world"-like microservice that demonstrate how to use Payara Micro with some of JavaEE7 specs.
it's a RESTful webservice built using Jax-rs, JPA, H2 embedded database and deployed with the payara-micro JAR
<i>Payara Micro is designed for running Java EE applications in a modern containerized / virtualized infrastructure, using automated provisioning tools like Chef, Ansible or Puppet https://www.payara.fish/payara_micro</i><br/>
It will run WAR files without any server installation!

<b>What you will need:<b>
  - JDK 8
  - Maven
  - intelliJ (or any IDE)
  - payara-micro.jar file (get it from download page)
  
  <b>Deploying the service:</b>
  Put the Jar file in your project directory, generate the War file and use this command line:<br/>
  ```java -jar payara-micro.jar --deploy <path-to-your-war-file>```

# springtest
Testing sprint boot and spring insight

- Install latest STS 3.6.4
- Install and set up latest maven (3.2.5)
- Clone the source (git clone https://github.com/vambo/springtest.git)
- run mvn eclipse:eclipse
- In STS Import > Maven > Existing Maven Projects
- In STS create a new server instance, select the insight template
- Several ways to build&deploy the application:
  - Run "mvn package", copy springtest.war from /target to the tcserver /webapps folder
  - In STS choose "Run as" > "Run on server" and select the created tcServer instance
- Go to http://localhost:8080/springtest/greeting and spam it a few times
- You should see activity on http://localhost:8080/insight

## Restful Booker API Performance Testing
## About this project
Performance testing project using Apache JMeter on the Restful Booker API. Includes Load, Stress, and Endurance (Soak) testing to evaluate responsiveness, scalability, and stability under different traffic conditions.
## Objectives
-	Measure API response times under load
-	Identify breaking points under stress
-	Validate long-term stability (soak tests)
-	Detect bottlenecks and ensure SLA compliance
## Tools & Technologies
-	Apache JMeter – performance testing framework
-	Restful Booker API – target application
-	CSV Data Set Config – parameterization
-	JMeter Plugins – optional advanced metrics
## Prerequisites
-	Java Runtime Environment (JRE) installed
-	Latest Apache JMeter downloaded and configured
## API Documentation [Restful booker Api Dcumentation](https://restful-booker.herokuapp.com/apidoc/index.html)
## Test Scenarios
-	Load Test: 200 users, 15s ramp-up, 5 min duration
-	Stress Test: Scale 100 → 500+ users
-	Endurance Test: 200 users, extended duration stability check
## Metrics
-	Response Time (avg, 90th/95th percentile)
-	Throughput (requests/sec)
-	Error Rate (%)
-	Active Threads
## Reports
Generates HTML reports with:
-	Response Time Graphs
-	Throughput trends
-	Error %
-	Active Threads


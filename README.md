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
## API Documentation [Restful Booker API Dcumentation](https://restful-booker.herokuapp.com/apidoc/index.html)
## Test Scenarios
-	Load Test: 200 users, 15s ramp-up, 5 min duration
-	Stress Test: Scale 100 → 500+ users
-	Endurance Test: 200 users, extended duration stability check
## Metrics
-	Response Time (avg, 90th/95th percentile)
-	Throughput (requests/sec)
-	Error Rate (%)
-	Active Threads
## Metrics picture
<img width="1920" height="1080" alt="Metrics 2026-04-24 174205" src="https://github.com/user-attachments/assets/21009f48-6f20-4048-9790-0c3f2cc12f3e" />

## Reports
Generates HTML reports with:
-	Response Time Graphs
-	Throughput trends
-	Error %
-	Active Threads
## Reports pictures
<img width="960" height="540" alt="HTML REPORT1 163045" src="https://github.com/user-attachments/assets/24c4059b-f70a-41fb-9036-0ebf61e9031f" />
<img width="960" height="540" alt="HTML REPORT4 2026-04-25 163458" src="https://github.com/user-attachments/assets/eac0ef36-ae37-4849-9ed3-418e91877d9a" />
<img width="960" height="540" alt="HTML REPORT3 163349" src="https://github.com/user-attachments/assets/c3d4db62-1012-4635-afdf-f59552e20333" />
<img width="960" height="540" alt="HTML REPORT2 163231" src="https://github.com/user-attachments/assets/85ac6fad-d214-4a3d-8a81-58c7147ab2a8" />

## Test Execution Vedio

https://github.com/user-attachments/assets/4dd5fb6f-dc2e-4db3-bfb1-3f618c244502





  


# CloudDesignPatterns
## Bulk Head Pattern
Based on the partioning in ship to avoid sinking.When there is a slowness in any one of the service/service unavailability,instead of eventual shutodown of entire application isolate the service which has problem
![alt text](https://github.com/Arokia-Bhavya/CloudDesignPatterns/blob/main/bulkhead.png)
Implementation:- by deploying in seperate containers,by implementing bulkhead configurations using resilience4j jar
## Circuit Breaker Pattern
## Retry Pattern
## SAGA Orchestration
## SAGA Choreography


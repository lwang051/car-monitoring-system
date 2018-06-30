# Vehicle-Location-Monitoring-System
This is a system that monitors vehicles' locations on google maps. In real life vehicles are running on roads and real-time data such as the latitude and the longitude are gathered from the moving vehicles themselves, while in this project a simulation service is introduced as a substitution of the otherwise much heavier work.

The system simulates the moving/non-moving vehicles, and finally visualize the movement on google maps to the client. The business logic is simple, yet the whole system is built in microservice architecture. Services are well partitioned and isolated, communicating to each other through RESTful APIs. Application health monitoring, service registry/discovery, and circuit breaker are integrated into the system, and more needs to be considered to meet the industry standard and make it a full fledged application. This project is done using Java and Spring tech stack.
### Environment
1. 14G+ RAM (if running on one node)
2. Web Browser
3. Terminal/Command Line Tool
4. JRE 1.8
5. Maven
6. Docker
7. Postman
### Command
In Terminal/Command Line Tool, change the directory (cd) into the project directory (Vehicle-Location-Monitoring-System)
#### Build:

    cd monitoring-system
    mvn clean install
    cd ..
    cd operation-system
    mvn clean install
    cd ..

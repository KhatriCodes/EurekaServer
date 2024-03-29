# EurekaServer

Eureka Server is an application that holds the information about all client-service applications. Every Micro service will register into the Eureka server and Eureka server knows all the client applications running on each port and IP address. Eureka Server is also known as Discovery Server.

**Eureka Server Implementation Need Below Steps:**

* Need to add eureka server dependency
* In main class we have to keep @EnableEurekaServer
* Port and application name in properties file
* In YAML file we have to keep register with eureka as false

Here we have Design Eureka Server Application and 2 Clients Application i.e. [First Eureka Client](https://github.com/KhatriCodes/FirstEurekaClient) and [Second Eureka Client](https://github.com/KhatriCodes/SecondEurekaClient). And both Applications are registred in Eureka Server. Here we are calling Second Eureka Client from First Eureka Client with the name instead of host name and port Number.

**Block Diagram**
![EurekaServer](https://github.com/KhatriCodes/EurekaServer/blob/master/EUREKA_SERVER_BLOCK_DIAGRAM.png)

[ScreenShots](https://github.com/KhatriCodes/EurekaServer/blob/master/Eureka%20Server%20Demo%20SS.docx?raw=true)


# Docker
![](engine-components-flow.png)

### What is Docker
Docker is an open-source platform that is designed to be lightweight and simple. A Docker container is a standardized unit of software used to deploy applications. 

### Pros
- Containers are small compared to Virtual Machines
- Containers use less resources
- Fast boot
- Stable
- Eliminate the issues of "Works on my machine" (but not on different environmnet)
- Works well in DevOps and CI/CD

### Cons
- Security - Since there's no Operating System, security aspects of containers get overlooked
- Isolation - Containers use the same kernel so they are not completely isolated from each other
- Networking can be tricky when we want to limit access within containers and also have proper network communications
- Advances Quickly - Sometimes documentation change too quick, before the industry has a chance to adapt
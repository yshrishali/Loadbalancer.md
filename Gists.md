# Loadbalancer.md

## Loadbalancer-- load balancing is defined as the methodical and efficient distribution of network or application traffic across multiple servers in a server farm. 
* It is divided into two main parts
* 1)Application Load Balancer(ALB). Deals with Webservices like HTTP/HTTPS
* 2) Network Load Balancer(NLB) Deals with Database. 
  **TCP
  **TLS
* HTTP can work with NLB also , but not  vice versa.
# Difference between ALB and NLB
## Application Load Balancer (ALB)
This is the distribution of requests based on multiple variables, from the network layer to the application layer. It is context-aware and can direct requests based on any single variable as easily as it can a combination of variables. Applications are load balanced based on their peculiar behavior and not solely on server (operating system or virtualization layer) information.

## Network Load Balancer (NLB)
* This is the distribution of traffic based on network variables, such as IP address and destination ports. It is layer 4 (TCP) and below and is not designed to take into consideration anything at the application layer such as content type, cookie data, custom headers, user location, or the application behavior.
* 
# OSI Layers

* IT stands for Open System Interconnection. 
* It  is a reference model that describes how information from a software application moves through a physical medium from one computer to  another computer.
* OSI model divides the whole task into seven smaller and manageable tasks. Each layer is assigned a particular task.

  * ![image](https://user-images.githubusercontent.com/83238288/116670295-2d5e4d00-a9bd-11eb-8cb7-45ca0cb57dee.png)

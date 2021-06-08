# Cluster Consul Installation

## First i install consul, using brew

![1](./1.png)

## I created the infrastructure on azure
![2](./2.png)

## Here I generated consul keygen, and tls files
![3](./3.png)
![4](./4.png)
![5](./5.png)

## I copied the files to my local machine to copy these to the vm where corresponds, using ansible
![6](./6.png)

## Here we can see the files on local machine in sublime text
![7](./7.png)

## I executed the ansible playbook
![8](./8.png)

## In this step is executed the bootstrap commands, but the client never shows a good functioning
![9](./9.png)
![10](./10.png)
![11](./11.png)
![12](./12.png)
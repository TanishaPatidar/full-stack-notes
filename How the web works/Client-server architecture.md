**Client**-A computer or system which is sending request to the server using domain name(ww.google.com)
 Ex-mobile,IT devices, PC,Laptops etc.

**Server**- First domain name is converted into IP address using DNS(Domain name system) then this Ip address is end to the server to get the response.

**Get Ip address using command Prompt**

1)ipconfig- get Ip address of pc

2)Nslookup domain name-to get the ip address of any url

ex- Nslookup www.freecodecamp.org

Non-authoritative answer:
Name:    www.freecodecamp.org
Addresses:  2606:4700:91bb:44a8:d342:0:652f:76d6
          104.26.2.33
          104.26.3.33
          172.67.70.149

3)Localhost-127.0.0.1
ex- http://localhost:4000(port no)
port number could be any thing.

4)tracert google.com-to know how many server are used to proceess reuest

**Types of Clinet-server architecture**

1) 1-tier-In this user Interface,bussiness logic and database are grouped into single entity.
2) 2-tier -In this user Interface and bussinness logic and group into one entity and database is put into another entity.
3) 3 tier-All the things are put into diffrernt entities.3-tier architecture more secure, has invisible database structures, and ensures data integrity.

**Advantages of Client-Server Architecture**
1)Management is Easy
2)Easily Accessible
3)Servers are Scalable
4)Centralized Control 
5)Security

**Disadvantages of Client-Server Architecture**
1)Requires Regular Maintenance
2)Requires Cost 
3)Network Congestion 


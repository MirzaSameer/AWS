1. create multiple EC2 instances. Here I'm using windows servers.

![image](https://github.com/MirzaSameer/AWS/assets/97332699/dbb49de5-5770-4989-8f3e-69d64682d32b)

2. Install httpd for linux and IIS server for windows

3. Make sure SSH/RDP, HTTP, and HTTPS are allowed in the security group

4. Create index.html file. If you're using Linux, you wll need to install https and if you're using windows install IIS server.

5. Now create a target group for load balancer. The targer group will have all the instances you need to bind with the load balance.
![image](https://github.com/MirzaSameer/AWS/assets/97332699/9682168e-b333-410c-84c7-7d6977c04bc7)
![image](https://github.com/MirzaSameer/AWS/assets/97332699/3b490fba-7b48-4a5d-97da-baee41c72ed2)
![image](https://github.com/MirzaSameer/AWS/assets/97332699/5e59cfc8-228a-438d-b490-5f631c995a79)
![image](https://github.com/MirzaSameer/AWS/assets/97332699/aca6c529-a3f1-4064-bbd1-f34e7410427a)
![image](https://github.com/MirzaSameer/AWS/assets/97332699/51bc1bd2-5acb-4f57-a0bc-3c5df1887d6d)



6. Create a load balancer and choose the type. Here I'm using NLB (NETWORK LOAD BALANCER)

![image](https://github.com/MirzaSameer/AWS/assets/97332699/df9e7a2b-bc14-4780-96c1-1e2fd1180f60)
![image](https://github.com/MirzaSameer/AWS/assets/97332699/c5bee8d2-1570-44bb-8fd1-ca952db9d16d)
![image](https://github.com/MirzaSameer/AWS/assets/97332699/a7394b62-5cda-47af-b078-ed5be5d0f5fc)


7. You need to select the target group here. One target group cannot be assigned to multiple load balancers at the same time.


![image](https://github.com/MirzaSameer/AWS/assets/97332699/8e826cfe-c0ad-4179-b6f7-af069cb1c1c5)

Here is the output of the two servers I've created and load balancing is working.

![image](https://github.com/MirzaSameer/AWS/assets/97332699/4e7fdf6f-dcc3-4425-95f7-11934f6cbb8a)

![image](https://github.com/MirzaSameer/AWS/assets/97332699/9ff36a6f-8b85-49a1-bd90-07c9f46cce12)


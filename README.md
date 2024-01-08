# k3s_installation


#on Master Node 
![Screenshot (1467)](https://github.com/MayadaMagdy24/k3s_installation/assets/93229250/90ffa749-e452-4e47-b6bf-520375d5b4e1)

--------------------------------------------------------

#on Worker Node

![Screenshot (1468)](https://github.com/MayadaMagdy24/k3s_installation/assets/93229250/b8b0c63c-ce2c-4c78-b601-2ca4d5be4009)

--------------------------------------------------------

- Access to kubernetes API is restricted to number of IP addresses. 
- Deploy nginx ingress - https://github.com/kubernetes/ingress-nginx/.

![Screenshot (1470)](https://github.com/MayadaMagdy24/k3s_installation/assets/93229250/5e797a8e-9772-4412-a975-087e4cf952b5)

- Validation

![Screenshot (1471)](https://github.com/MayadaMagdy24/k3s_installation/assets/93229250/e34768ba-9b35-4971-959c-5a7112e904e9)

------------------------------------------------------

- Deploy "Juice Shop" application, you can use official docker image from ‘bkimminich/juice-shop’.
- Expose “Juice Shop” application inside the cluster using a service.

![Screenshot (1475)](https://github.com/MayadaMagdy24/k3s_installation/assets/93229250/8d0e39db-75b8-49de-bc10-48587ffa6a3f)

![Screenshot (1474)](https://github.com/MayadaMagdy24/k3s_installation/assets/93229250/feacb568-35c3-43f4-a6c4-ebc545884aef)

- Validation
  ![image](https://github.com/MayadaMagdy24/k3s_installation/assets/93229250/1b6a2ccc-488d-4aa5-9d87-28e58f155cf1)
  
---------------------------------------------------------

- Expose “Juice Shop” application to outside the cluster using the nginx ingress.

![image](https://github.com/MayadaMagdy24/k3s_installation/assets/93229250/b7baea88-2917-41cf-8e64-ff42e70f07c7)

![image](https://github.com/MayadaMagdy24/k3s_installation/assets/93229250/2b41026b-d8a0-4083-8c21-167b7b2de880)


- Validation
  
![image](https://github.com/MayadaMagdy24/k3s_installation/assets/93229250/96afef8f-b15c-408e-83b5-a07a568fa7d3)








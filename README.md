# prometheus-task
## Lab1
1)minikube start

2)prometheus operator installed:

i)helm repo add prometheus-community https://prometheus-community.github.io/helm-charts  

ii)helm repo update   

iii)helm install monitoring prometheus-community/kube-prometheus-stack -n monitoring --create-namespace  

3)Access prometheus   

kubectl port-forward svc/prometheus-operated -n monitoring 9090:9090

<img width="677" height="353" alt="image" src="https://github.com/user-attachments/assets/5ebe8442-113d-4c7f-88c5-23e45e5eaa97" />


4)PromQL queries:


<img width="956" height="385" alt="image" src="https://github.com/user-attachments/assets/03a6c095-14e2-4f3a-b8d7-050ed62936a9" />  



<img width="944" height="401" alt="image" src="https://github.com/user-attachments/assets/14349a61-b669-45f4-9b3f-cc2c80350529" />  



<img width="959" height="404" alt="image" src="https://github.com/user-attachments/assets/98bbe9bb-aae3-45ae-90f8-178557eeebd8" />


pods that are not Running  



<img width="953" height="403" alt="image" src="https://github.com/user-attachments/assets/5ed9bbdd-cb42-4b74-b78a-e2f6d87485f5" />


## lab 2

![WhatsApp Image 2025-09-06 at 11 05 37_371bea71](https://github.com/user-attachments/assets/740ee8c6-bee8-4dd1-b995-6b5ad7de1ff5)


![WhatsApp Image 2025-09-06 at 11 42 43_c0c02f44](https://github.com/user-attachments/assets/7f47a5bb-8c82-4492-b161-65db788b77f5)



![WhatsApp Image 2025-09-06 at 11 49 42_2b392dad](https://github.com/user-attachments/assets/b858df12-b2b7-482b-9178-6dcfe91db8fb)

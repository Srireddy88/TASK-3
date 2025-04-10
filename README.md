# TASK-3 DAY-3

# Infrastructure as Code (IaC) with Terraform

## Tools Used

- **Terraform**
- **Docker**

---

## Deliverables

- `main.tf` (Terraform configuration file)
- ![Screenshot 2025-04-10 174350](https://github.com/user-attachments/assets/6fd613c2-a3b9-4ce0-a9d4-9434358cc1bd)

- Execution logs (Terraform & Docker CLI commands)

---

## Install Terraform and Docker 

```bash
terraform --version (to check terraform version)
docker -v (to check docker version)
```
## Commads used 
```bash
  terraform init                 (Initialing Terraform working directory(TASK-3))
```
![Screenshot 2025-04-10 173016](https://github.com/user-attachments/assets/2add193a-5798-4b2f-a27c-1a36f411368c)
```bash
  terraform plan              
  terraform apply -auto-approve  (Apply configuration to create resources)
  docker ps                      (Check running Docker containers)
  ```
![Screenshot 2025-04-10 173121](https://github.com/user-attachments/assets/975fefce-3e7b-4609-98e9-587a79d2fdc3)
  ```bash
  terraform state list           (Show tracked resources)
  terraform destroy -auto-approve (Destroy the resources which are created)
```
![Screenshot 2025-04-10 174756](https://github.com/user-attachments/assets/051389c9-5ce2-4ce2-bae2-0ac67bff36c5)

## Final Output : 

![Screenshot 2025-04-10 173000](https://github.com/user-attachments/assets/83fb0861-e557-4913-af56-b847c01a53d9)




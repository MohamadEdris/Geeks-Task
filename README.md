# Geeks Task
Used the following tutorial: https://www.geeksforgeeks.org/profile-application-using-python-flask-and-mysql/

1) Containerize the application
2) Run in a kubernetes cluster
3) Use a jenkins pipeline to push the image automatically to DockerHub

## Run Using Docker Compose

Clone the project

```bash
    git clone https://github.com/MohamadEdris/Geeks-Task.git
```

Go to the project directory

```bash
  cd Geeks-Task
```

Build

```bash
  docker compose up
```

Run

```bash
  http://127.0.0.1:5000/
```
## DockerHub repository:
![image](https://user-images.githubusercontent.com/73100170/183134525-6ef7adfa-2e17-4dc8-a9ba-c29226834ad8.png)


## kubernetes 

Start minikube

```bash
  minikube start
```

Enable ingress

```bash
  minikube addons enable ingress
```

Apply yml files

```bash
  kubectl apply -f .
```

To run on localhost

```bash
  minikube tunnel
```




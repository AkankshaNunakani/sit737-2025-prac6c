## Cloud-Native App with Kubernetes
This project demonstrates deploying a simple Node.js application to a Kubernetes cluster, interacting with it via kubectl, and updating it using best practices of CI
# Part I :Interact with the Deployed Application
Used commands 
kubectl get pods
kubectl get services
# Part II Updating the App
To update the application:
1.  the code in app.js

2. Build a new Docker image with a new tag (e.g., v3)

3. Push it to DockerHub

4. Update deployment.yaml with the new image tag

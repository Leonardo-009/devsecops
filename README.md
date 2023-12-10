### devsecops
### docker build -t secops .
### docker run -d -p 8080:8080 -p 50000:50000 --name secops-container secops
### http://localhost:8080
### http://localhost:8080/blue

### docker exec -it <container_id> cat /var/jenkins_home/secrets/initialAdminPassword
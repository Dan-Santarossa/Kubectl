# Kubectl

Kubernetes Project Steps
----------------------------------

BASIC

Using the command line, 

1. create a deployment that runs the nginx image.
2. Display the details of this deployment
3. check the event logs from the deployment
4. delete the deployment

ADVANCED

1. Create the same deployment using a yaml file
2. Display the details of this deployment via the command line
3. Update the yaml file to scale the deployment to 4 nginx containers
4. Verify the change via the command line

COMPLEX

1. Create a multi-container pod that runs nginx and Debian containers
2. Expose port 80 in nginx container
3. Mount any local directory to the nginx container so it is available inside the container
4. Create a NodePort service using port 80

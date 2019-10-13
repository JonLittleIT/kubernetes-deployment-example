# Description

This repo was created to suport files for this article



The idea here is to use these two deployment yaml kubernetes files to make local and live deployments. We are going to create two services, one for Mysql and another for a simple WordPress. Each ones will be comunicated

# Creating deployment

kubectl apply -f ./mysql-deployment.yaml
kubectl apply -f ./wordpress-deployment.yaml 

# Checking deployment status

kubectl get deployments

# Describing WordPress service

kubectl describe services wordpress

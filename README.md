# gratefuldog3
EKS terraform deployment


## access keys
`aws configure --profile robert-eks`
aws sts get-caller-identity --profile robert-eks

##
`kubectl auth can-i "*" "*"`


aws eks update-kubeconfig \
  --name gratefuldog3 \
  --region us-east-1 \
  --profile eks-admin

- sample app: https://docs.aws.amazon.com/eks/latest/userguide/alb-ingress.html


## links
https://www.youtube.com/watch?v=kRKmcYC71J4
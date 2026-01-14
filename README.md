 ;   TO INSTALL INGRESS CONTROLLER, FIRST WE HAVE TO INSTALL NGINX INGRESS CONTROLLER:

  kubectl create -f  https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.2.1/deploy/static/provider/cloud/deploy.yaml
              

               
  kubectl get ns                               ; check new ingress name space will be created .with ingress controller installed
  kubectl get all -n ingress-nginx             ; you will get here 3 pods ,controller ,admission ,deploy, RS, job as well 
  yum install git -y
                  

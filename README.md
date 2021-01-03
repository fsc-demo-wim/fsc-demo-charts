# fsc-demo-charts
helm charts repo to deploy fsc-demo

## package 

helm package ./fsc-demo-charts

## deploy charts for fsc-demo app

helm install fsc-demo fsc-demo-0.1.0.tgz -n fsc

## destroy the deployment

helm delete -name fsc-demo  -n fsc

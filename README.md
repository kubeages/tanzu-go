# Go Sample App using Tanzu Application Platform

## Creating the workload

`tanzu apps workload create -f config/workload.yaml -y`

## Checking the workload

`tanzu apps workload get tanzu-go`

## Viewing

`curl https://tanzu-go.<YOUR_DOMAIN>`

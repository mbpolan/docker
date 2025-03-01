# Runiac Containers

## alpine-full (kitchen sink)

This is the default container for runiac and is configured to handle most cloud deployments to Azure or GCP.

- Terraform
- Runiac
- Azure CLI
- GCloud SDK
- Bash, wget, curl, jq, ca-certs

## alpine

A lightweight container with no cloud specific SDKs

- Terraform
- Runiac
- Bash, wget, curl, jq, ca-certs

## alpine-azure

An azure optimized container

- Terraform
- Runiac
- Azure CLI
- Bash, wget, curl, jq, ca-certs

## alpine-gcp

A GCP optimized container

- Terraform
- Runiac
- Azure CLI
- Bash, wget, curl, jq, ca-certs

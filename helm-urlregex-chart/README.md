# FLEET-64 and FLEET-65 Testing Data

This directory contains the `fleet.yaml` file which uses a local helm registry and the chart `app-0.1.0.tgz`. These are deployed on the same cluster under test. 

The complete registry and its data can be provisioned using the "Import YAML" button in Rancher. The current version for the registry can be found at the following location:

[https://github.com/rancher/fleet-e2e/blob/main/tests/assets/helm-server-with-auth-and-data.yaml](https://github.com/rancher/fleet-e2e/blob/main/tests/assets/helm-server-with-auth-and-data.yaml)

## Helm Repo Credentials

- User: `user`
- Password: `password`

## Helm Repo URL

[http://nginx-service.default.svc.cluster.local](http://nginx-service.default.svc.cluster.local)

## Helm Chart Details

- Name: `app`
- Version: `0.1.0`
- Full URL for chart: [http://nginx-service.default.svc.cluster.local/app-0.1.0.tgz](http://nginx-service.default.svc.cluster.local/app-0.1.0.tgz)

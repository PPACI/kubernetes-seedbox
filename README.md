# kubernetes-seedbox

Kubernetes based seedbox

# Deploy

1. `kubectl apply -f ./generic`
2. `kubectl apply -f ./transmission`

# Notes

* Default `generic/storage-class.yaml` deploy a storage class based on K3S `local-path`
but with `ReclaimPolicy: Retain`.


# Roadmap

1. Deploy everything with flat hardcoded files to iterate quickly.
2. Create a Helm chart to enable people to customize everything.
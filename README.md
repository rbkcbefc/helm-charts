[quick-start]: https://helm.sh/docs/intro/quickstart/

# Helm Docs
[quick-start]

# Generate K8s manifests
helm template mock-email-service

# Install Chart
helm install mock-email-service mock-email-service

# Verify
Once the chart is installed, port-forward 8080 and run the test
1. kubectl port-forward svc/mock-email-service-service 8080:8080
1. helm test mock-email-service

Once the chart is installed, port-forward 8080 and run the test
a. kubectl port-forward svc/mock-email-service-service 8080:8080
b. helm test mock-email-service

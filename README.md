# Service-Mesh-Microservices-Platform
Deploy micro-services on Kubernetes with Istio handling traffic, security, and observability.

# Service mesh architecture

# Secure inter-service communication

# Production-level monitoring

Features to Implement : 
  1. mTLS between services using Istio
  2. Traffic splitting (90% v1, 10% v2)
  3. Circuit breaking + retries
  4. Fault injection (simulate 500 errors)
  5. Distributed tracing with Jaeger
  6. Metrics with Prometheus
  7. Dashboards in Grafana

istio-microservices-platform/
 ├── k8s-manifests/
 ├── istio/
 │    ├── gateway.yaml
 │    ├── virtualservice.yaml
 │    ├── destinationrule.yaml
 ├── monitoring/
 ├── load-tests/
 └── README.md (architecture diagram + testing proof)


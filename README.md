The Langfuse Helm Chart deploys a complete, production-ready Langfuse stack on Kubernetes with all required backend services:

PostgreSQL – Stores application metadata, traces, and structured data.

ClickHouse – Handles high-performance analytics and event storage.

MinIO – Provides S3-compatible object storage for logs, blobs, and artifacts.

Valkey – Acts as an in-memory cache and queue system (Redis-compatible) for fast data access and background processing.

This chart simplifies deployment by bundling all core dependencies, enabling scalable, observable, and reliable Langfuse operations in Kubernetes environments.

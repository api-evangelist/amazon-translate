---
title: "Monitor and debug generative AI inference with SageMaker detailed metrics and Insights dashboard on CloudWatch"
url: "https://aws.amazon.com/blogs/machine-learning/monitor-and-debug-generative-ai-inference-with-sagemaker-detailed-metrics-and-insights-dashboard-on-cloudwatch/"
date: "2026-06-18"
author: "Apoorva Chandra"
feed_url: "https://aws.amazon.com/blogs/machine-learning/feed/"
---
Amazon SageMaker AI now emits over 100 detailed inference metrics to CloudWatch, enabling teams to monitor GPU health, token-level latency, KV cache pressure, and traffic distribution across availability zones. The built-in SageMaker Insights dashboard provides three monitoring views—Performance, Capacity, and Reliability—for both single-model and inference component endpoints, with features like per-instance hexagon displays, latency breakdown, fleet utilization tracking, and cold start diagnostics. Metrics flow in OpenTelemetry format and are queryable via PromQL, enabling integration with external observability platforms like Grafana and Datadog.

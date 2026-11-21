# Awesome Log Management

A curated directory of log management, log analytics and log-pipeline tools, SaaS and open source.

## 📑 Table of Contents

- [Cloud-Native Logging (2)](#cloud-native-logging)
- [Log Analytics & Search (2)](#log-analytics--search)
- [Log Management SaaS (7)](#log-management-saas)
- [Log Pipelines & Collectors (4)](#log-pipelines--collectors)
- [Low-Cost Log Storage (1)](#low-cost-log-storage)
- [Open-Source Log Stacks (5)](#open-source-log-stacks)


## Cloud-Native Logging

- [Axiom](https://axiom.co/) - Cloud-native log data platform that stores event data in object storage and enables SQL-like querying. Designed for engineering teams handling high-volume observability data with separate compute and storage. Offers self-hosted and managed options with usage-based pricing. ([Read more](/details/axiom.md)) `Freemium` `Paid` `API` `Cloud-Native` `Self-Hosted`
- [VictoriaLogs](https://victoriametrics.com/products/victorialogs) - Log storage and search solution by VictoriaMetrics optimized for high ingestion rates and low resource usage. Compatible with common log agents and offers a Prometheus-like operational model. Available as open-source binary and managed cloud service. ([Read more](/details/victorialogs.md)) `Open Source` `Self-Hosted` `Low-Cost` `Cloud-Native`

## Log Analytics & Search

- [Elastic](https://www.elastic.co/) - Open core search and analytics engine built on Elasticsearch and Kibana for log storage, search, and visualization. Provides the Elastic Stack for SIEM, observability, and enterprise search. Available as a managed cloud service or self-managed distribution with free and paid tiers. ([Read more](/details/elastic.md)) `Freemium` `Self-Hosted` `API` `Open Source` `Enterprise`
- [Splunk](https://www.splunk.com/) - Data analytics platform for searching, monitoring, and analyzing machine-generated data including logs. Widely used in enterprise security and IT operations for indexing large volumes of unstructured data. Offers cloud and self-hosted deployment with commercial licensing. ([Read more](/details/splunk.md)) `Paid` `Enterprise` `API` `AI-Powered` `Self-Hosted`

## Log Management SaaS

- [Better Stack Logs](https://betterstack.com/) - Modern log management SaaS offering log collection, search, dashboards, and alerting. Built for developers and DevOps teams with a focus on ease of use and fast setup. Provides a free tier and paid plans based on ingestion volume. ([Read more](/details/better-stack-logs.md)) `Freemium` `Free Plan` `API` `Cloud-Native`
- [Datadog Log Management](https://www.datadoghq.com/) - Cloud-based log management and observability platform that aggregates, indexes, and analyzes logs from cloud, hybrid, and on-premises environments. Suitable for DevOps and SRE teams needing real-time search, alerting, and correlation with metrics and traces. Paid enterprise SaaS with usage-based pricing. ([Read more](/details/datadog-log-management.md)) `Paid` `Enterprise` `API` `AI-Powered` `Cloud-Native`
- [Loggly](https://www.loggly.com/) - Cloud-based log management service for aggregating and searching logs from applications and servers. Provides automated parsing, dashboards, and alerts with a focus on simplicity for DevOps teams. Owned by SolarWinds with tiered paid plans. ([Read more](/details/loggly.md)) `Paid` `API` `Cloud-Native`
- [Logz.io](https://logz.io/) - Log management and observability SaaS built on open-source Elasticsearch, Logstash, and Kibana. Offers log search, infrastructure monitoring, and security analytics with a multi-tenant cloud architecture. Provides a free tier and paid plans. ([Read more](/details/logz-io.md)) `Freemium` `Paid` `API` `Open Source` `Cloud-Native`
- [Papertrail](https://www.papertrail.com/) - Hosted log management service that aggregates logs from servers, cloud services, and applications into a searchable web interface. Owned by SolarWinds, it targets small to mid-sized teams needing simple log tailing and alerts. Pricing is based on log volume and retention. ([Read more](/details/papertrail.md)) `Paid` `API` `Cloud-Native`
- [Sematext Logs](https://sematext.com/logs) - Log management and analytics SaaS with agent-based collection, full-text search, and alerting. Part of the Sematext observability suite and integrates with Elasticsearch-compatible APIs. Offers cloud and self-managed options with tiered pricing. ([Read more](/details/sematext-logs.md)) `Freemium` `Paid` `API` `Cloud-Native`
- [Sumo Logic](https://www.sumologic.com/) - Cloud-native SaaS platform for log analytics, observability, and security. Provides real-time search, machine learning-based anomaly detection, and integrations with AWS, Kubernetes, and CI/CD tools. Offers a free tier and paid enterprise plans. ([Read more](/details/sumo-logic.md)) `Freemium` `Paid` `Enterprise` `API` `AI-Powered`

## Log Pipelines & Collectors

- [Cribl Stream](https://cribl.io/) - Observability pipeline tool for collecting, reducing, and routing log and metric data to multiple destinations. Provides a visual interface for data transformation and schema-on-write capabilities. Offers a free community edition and paid enterprise licenses. ([Read more](/details/cribl-stream.md)) `Freemium` `Paid` `Enterprise` `API` `Self-Hosted`
- [Fluent Bit](https://fluentbit.io/) - Fast, lightweight log processor and forwarder for cloud-native and embedded environments. CNCF project written in C with minimal memory footprint, often deployed as a DaemonSet on Kubernetes. Open source under Apache 2.0. ([Read more](/details/fluent-bit.md)) `Open Source` `Self-Hosted` `Cloud-Native` `API`
- [Fluentd](https://www.fluentd.org/) - Open-source data collector for unifying log collection and forwarding across hybrid environments. Part of the Cloud Native Computing Foundation with a large plugin ecosystem for inputs and outputs. Written in Ruby and designed for reliability. ([Read more](/details/fluentd.md)) `Open Source` `Self-Hosted` `Cloud-Native` `API`
- [Vector](https://vector.dev/) - High-performance observability data pipeline for collecting, transforming, and routing logs and metrics. Written in Rust and designed for cloud-native environments with minimal resource usage. Open source under the Apache 2.0 license. ([Read more](/details/vector.md)) `Open Source` `Self-Hosted` `Cloud-Native` `API`

## Low-Cost Log Storage

- [Quickwit](https://quickwit.io/) - Open-source search engine built for observability and object storage, using Apache Lucene and Tantivy. Designed for cost-effective log storage on S3-compatible backends with minimal operational overhead. Suitable as a Loki or Elasticsearch alternative. ([Read more](/details/quickwit.md)) `Open Source` `Self-Hosted` `Cloud-Native` `Low-Cost`

## Open-Source Log Stacks

- [Apache OpenSearch](https://opensearch.org/) - Open-source search and analytics suite forked from Elasticsearch and Kibana, licensed under Apache 2.0. Used for log analytics, search, and observability with community-driven development. Supported by AWS and available as a managed service or self-hosted. ([Read more](/details/apache-opensearch.md)) `Open Source` `Self-Hosted` `Free Plan` `API` `Enterprise`
- [Grafana Loki](https://grafana.com/oss/loki) - Open-source log aggregation system designed to store logs and index metadata rather than full text. Integrates tightly with Grafana for visualization and Prometheus for metrics. Optimized for cost-effective log storage in Kubernetes and cloud-native environments. ([Read more](/details/grafana-loki.md)) `Open Source` `Self-Hosted` `Cloud-Native` `API`
- [Graylog](https://www.graylog.org/) - Centralized log management platform for collecting, indexing, and analyzing machine data. Provides a web interface, alerting, and stream processing with an open-source core and commercial enterprise features. Supports self-hosted deployment. ([Read more](/details/graylog.md)) `Open Source` `Self-Hosted` `Freemium` `Enterprise` `API`
- [OpenObserve](https://openobserve.ai/) - Open-source observability platform for logs, metrics, and traces built on ClickHouse and object storage. Provides a unified UI for log search and dashboarding with low storage costs. Can be self-hosted or used via managed cloud. ([Read more](/details/openobserve.md)) `Open Source` `Self-Hosted` `Low-Cost` `Cloud-Native`
- [SigNoz](https://signoz.io/) - Open-source observability platform for logs, traces, and metrics using ClickHouse as the storage backend. Offers a self-hosted alternative to commercial APM tools with log search and visualization. Available under an open-source license with a managed cloud option. ([Read more](/details/signoz.md)) `Open Source` `Self-Hosted` `Cloud-Native` `Free Plan`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This work may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this work, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
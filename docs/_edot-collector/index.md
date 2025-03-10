---
title: Overview
layout: default
nav_order: 1
---

# EDOT Collector

The **Elastic Distribution of OpenTelemetry (EDOT) Collector** is an open-source distribution of the [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector).

Built on OpenTelemetry’s modular [architecture](https://opentelemetry.io/docs/collector/), the EDOT Collector offers a curated and fully supported selection of Receivers, Processors, Exporters, and Extensions. Designed for production-grade reliability. 

## 🚀 Get started
The quickest way to get started with EDOT is to follow our [quick start guide](https://github.com/elastic/opentelemetry/blob/miguel-docs/quickstart-guide.md).

## 🎛️ Collector configuration
The EDOT collector can be configured using the standard OTel collector configuration file or values.yml if you have deployed using Helm.

For full details on each option visit [this page](_edot-collector/edot-collector-config.md)

## 🧩 EDOT Collector components

The Elastic Distribution of OpenTelemetry (EDOT) Collector is built on OpenTelemetry’s modular architecture, integrating a carefully curated selection of Receivers, Processors, Exporters, and Extensions to ensure stability, scalability, and seamless observability. 

Visit [this page](https://github.com/elastic/elastic-agent/tree/main/internal/pkg/otel#components) for the full list of components

### Request a component to be added
To request a component to be added to EDOT Collector, please submit a [github issue](https://github.com/elastic/opentelemetry/issues/new/choose).

## Collector Limitations
The EDOT collector has some limitations which are mostly inherited from the upstream components, see the [full list](_edot-collector/edot-collector-limitations.md) here before troubleshooting.

### 📄 License
View details of license for [EDOT Collector](https://github.com/elastic/elastic-agent/blob/main/LICENSE.txt). 
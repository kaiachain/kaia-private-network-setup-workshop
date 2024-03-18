---
title: "System Requirement"
date: 2022-09-20T17:44:45+09:00
weight: 20
pre: "<b>B. </b>"
draft: false
---
{{< line_break >}}
### 1. System Requirement (for cloud)

>Recommended Specification for AWS

| Node Type | Model | vCPU | Memory (GiB) | Storage size (GiB) | Storage speed (IOPS) | Price (Seoul region, USD/h) |
| --- | --- | --- | --- | --- | --- | --- |
| CN | m6i.8xlarge | 32 | 128 | 4,000 (Minimum) | 4,000 (Minimum) | 1.92 |
| PN (with Live Pruning DB) | m6i.2xlarge  | 8 | 32 | 3,500 (Minimum) | 4,000 (Minimum) | 0.472 |

{{< line_break >}}
>Recommended Specification for Azure

| Node Type | Model | vCPU | Memory (GiB) | Storage size (GiB) | Storage speed (IOPS) | Price (Seoul Central, USD/h) |
| --- | --- | --- | --- | --- |---|---|
| CN | D32s v5 | 32 | 128 | P50 (4096) | 7500 | 1.625 |
| PN (with Live Pruning DB) | D8s v5 | 8 | 32 | P50 (4096) | 7500 | 0.472 |

{{< line_break >}}
>Recommended Specification for GCP

| Node Type | Model | vCPU | Memory (GiB) | Storage size (GiB) | Storage speed (IOPS) | Price (Seoul Central, USD/h) |
| --- | --- | --- | --- | --- |---|---|
| CN | n2-standard-32 | 32 | 128 | 4,000 | 4,000 (Minimum) | 1.625 |
| PN (with Live Pruning DB) | n2-standard-8 | 8 | 32 | 3,500 (Minimum) | 4000 | 0.508121 |

{{< line_break >}}
{{< line_break >}}

---
{{< line_break >}}
*If you would like to check the detailed requirements or use an on-premise server, please refer to the link below.*
>https://docs.klaytn.foundation/docs/nodes/core-cell/system-requirements/

{{< line_break >}}
{{< line_break >}}
{{< line_break >}}
If you finish check requirements, please click the next button ```>``` on the right side of this page.

# Phase 0 environment (built 2026-10-29)

Host: Beelink SER5 (Ryzen 5 5500U, 16 GB), Windows 11 + WSL2 (10 GB / 8 threads)
Ubuntu 24.04.5 LTS | Terraform v1.17.1 | Google Cloud SDK 591.0.0 | Helm v3.22.1
k3s v1.34.12+k3s1 (containerd 2.2.7) | Docker 29.1.3 | Python 3.12.3

GCP project: notional-analog-384113, region us-central1
Quotas: GPUS_ALL_REGIONS 1 (approved 2026-10-29), NVIDIA_L4_GPUS 1,
PREEMPTIBLE_NVIDIA_L4_GPUS 1, CPUS 200, CPUS_ALL_REGIONS 32
Budget: "AI Factory RAG", monthly, alerts at 50/90/100%

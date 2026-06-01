# NOTE

You should use a well-known Iranian domain instead of a direct IP address, so blocking ports 80 and 443 on that website or application becomes less feasible.

# 🌐 Internet Layer Model (Simplified View)

┌──────────────────────────────────────┐
│ 1) APPLICATION LAYER │
│ (Sites & Services) │
│ │
│ YouTube, Aparat, Google, etc │
└──────────────────────────────────────┘
│
▼
┌──────────────────────────────────────┐
│ 2) CONTENT / POLICY LAYER │
│ │
│ - Content licensing (geo-blocking) │
│ - Video / content restrictions │
│ - Country-based access rules │
└──────────────────────────────────────┘
│
▼
┌──────────────────────────────────────┐
│ 3) DNS / DOMAIN LAYER │
│ │
│ - Domain → IP resolution │
│ - Domain filtering │
│ - DNS manipulation │
└──────────────────────────────────────┘
│
▼
┌──────────────────────────────────────┐
│ 4) NETWORK FILTER LAYER │
│ │
│ - IP filtering │
│ - Port blocking (22, 443, etc) │
│ - VPS / datacenter restrictions │
└──────────────────────────────────────┘
│
▼
┌──────────────────────────────────────┐
│ 5) ROUTING / ISP LAYER │
│ │
│ - Internet routing decisions │
│ - International traffic shaping │
│ - Path selection / congestion │
└──────────────────────────────────────┘
│
▼
┌──────────────────────────────────────┐
│ 6) PHYSICAL INFRASTRUCTURE │
│ │
│ - Fiber cables & data centers │
│ - Cross-border infrastructure │
└──────────────────────────────────────┘

# ⚠️ IMPORTANT NOTICE

> USING THE MANAGEMENT PANEL TO CREATE AND MANAGE ACCOUNTS WITHIN XRAY FROM INSIDE IRAN IS NOT POSSIBLE.
>
> IT IS RECOMMENDED TO USE THE BPB METHOD TO FIND A CLEAN IP ADDRESS FOR COMMUNICATION WITH CLOUDFLARE WORKERS.

## Quick Start

```bash
bash <(curl -Ls https://raw.githubusercontent.com/Y4SIIIIN/V2Ray/main/install.sh)
```

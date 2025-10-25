# HNG Stage 2 DevOps Task - Blue/Green Deployment with Nginx

## Overview
This project deploys two Node.js apps (Blue & Green) behind Nginx with:
- **Auto failover** from Blue → Green on failure
- **Zero failed client requests**
- **Retry in same request**
- **Headers forwarded**: `X-App-Pool`, `X-Release-Id`

---

## How to Run

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/hng-stage2-devops.git
cd hng-stage2-devops
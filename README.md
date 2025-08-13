# Multi-Region AI Load Balancer

## Overview
I built a working MVP that routes inference requests across simulated GPU regions based on **latency** and **cost**.

- **Containerized** for easy deployment
- Supports simple model servers
- Dynamically reroutes requests to optimize **response time** and **regional compliance**

## How It Works
The system monitors latency and cost metrics across multiple simulated regions. When a request comes in, it routes the inference to the optimal region according to predefined policies.  

This allows:
- Faster responses during high traffic  
- Lower operational costs when certain regions are cheaper  
- Compliance with data locality requirements  

## What's Next
Right now, it’s just a simple MVP — but I see it evolving into a **middleware layer** between AI workloads and compute infrastructure.  

Think of it as a **traffic controller for inference** that dynamically balances:
- Quality of results  
- Cost efficiency  
- Compliance rules  
- Response time  

---

## 📹 Demo Video

<video src="ai-loadbalancer-demo.mp4" controls width="600">
  Your browser does not support the video tag.
</video>

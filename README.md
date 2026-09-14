---

## 📸 Architecture & Deployment Walkthrough

### 1. Cluster Initialization & Node Verification
The initial cluster bootstrap and verification confirming the local control-plane node is active and communicating properly.
<img width="1024" height="456" alt="image" src="https://github.com/user-attachments/assets/f9d07f45-3d90-421a-a2fc-683163185f79" />

### 2. Final Deployment Victory
Capturing the completed deployment rollout, container specifications, and healthy 1/1 Running pods with zero restarts.
![Deployment Success](assets/deployment-success.png)

---

## 🌐 Service Exposure & Live UI

### Minikube Service Tunnel
The terminal output showing the active local network tunnel, assigned target ports, and the generated loopback URL for service access.
![Minikube Tunnel](assets/minikube-tunnel.png)

### Kubernetes Demo Service UI
The browser view of the application dashboard displaying:
* **Deployment Info**: Confirming version `v1` and showing the specific active pod instance name handling incoming requests.
* **Simulate Load Section**: The interactive UI card featuring the **Generate Load** button used for testing cluster behavior and autoscaling.
![Service UI Dashboard](assets/service-ui.png)

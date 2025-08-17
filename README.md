# Task 7: Monitor System Resources Using Netdata

## 📌 Objective
To install and configure **Netdata** for monitoring system and application performance metrics in real time.

## 🛠 Tools Used
- **Netdata** (Free, open-source monitoring tool)
- **Docker** (for containerized deployment)

## 🚀 Steps Performed
1. Pulled and ran Netdata container:
   ```bash
   docker run -d --name=netdata -p 19999:19999 netdata/netdata

2. Accessed the Netdata dashboard at:

  http://localhost:19999

3. Monitored the following resources:

   CPU usage

   Memory utilization

   Disk I/O
  
  Network traffic

 Docker container stats

4. Explored alerts and chart panels to check real-time system health.

5. Verified logs inside /var/log/netdata.

📊 Deliverables

Screenshot of the Netdata dashboard with running metrics.

(Replace netdata_dashboard.png with your actual screenshot file name in the repo)

🎯 Outcome / Learning

Learned how to set up lightweight monitoring using Netdata.

Understood real-time visualization of system and container performance.

Gained hands-on exposure to using alerts and metrics for troubleshooting and capacity planning.
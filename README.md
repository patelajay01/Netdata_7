<img width="1812" height="931" alt="Screenshot 2025-08-15 102431" src="https://github.com/user-attachments/assets/152b8166-27f6-4a1f-9bc7-e20a31136a26" /># Task 7: Monitor System Resources Using Netdata

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
<img width="1812" height="931" alt="Screenshot 2025-08-15 102431" src="https://github.com/user-attachments/assets/efdecdc9-2ae2-4e1b-9e56-db01aea8ed16" />
<img width="1841" height="948" alt="Screenshot 2025-08-15 102515" src="https://github.com/user-attachments/assets/4e35937b-4f1f-484d-a1e6-801dc868f269" />
<img width="1862" height="949" alt="Screenshot 2025-08-15 102545" src="https://github.com/user-attachments/assets/72c4398e-ee67-4cc8-915a-7bd41231ba3f" />
<img width="1850" height="964" alt="Screenshot 2025-08-15 102404" src="https://github.com/user-attachments/assets/1625816d-b2f5-4d43-9d35-f1ea0bffa75f" />

5. Verified logs inside /var/log/netdata.


📊 Deliverables

Screenshot of the Netdata dashboard with running metrics.



🎯 Outcome / Learning

Learned how to set up lightweight monitoring using Netdata.

Understood real-time visualization of system and container performance.

Gained hands-on exposure to using alerts and metrics for troubleshooting and capacity planning.

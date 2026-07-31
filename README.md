SOC Lab Project

Objective:
The objective of this project is to build a home Security Operations Center (SOC) lab so as to simulate real world attack scenarios, test the detection rules and also to practice the incident response.

Architecture:
The phase of the project consists of and Ubuntu server running the Wazuh All in One deployment (Wazuh-Manager, Wazuh-Indexer and Wazuh-Dashboard)

Phase 1 : SIEM Deployment
In this phase, the Wazuh SIEM was successfully installed and configured.
Steps Taken :
a. Deployed Ubuntu server
b. Configured network bridging to allow external dashboard access.
c. Installed Wazuh using the all in one deployment script.
d. Successfully accessed the Wazuh dashboard.

Evidence:
a. Dashboard Overview <img width="1355" height="599" alt="wazuh dashboard" src="https://github.com/user-attachments/assets/03efd3c5-7737-4905-92ff-6df463e4d32d" />

Phase 2: Windows Endpoint & Agent Deployment
In this phase a Windows 11 Enterprise VM was deployed and connected to the Wazuh SIEM to act as our monitor at the endpoint.
Steps taken:
a. Deployed Windows 11 VM in Virtualbox with Bridged Networking.
b. Downloaded and installed the Wazuh Agent (V4.7.2) on Windows.
c. Registered the agent with the Wazuh-Manager automatically using the agent-auth.exe tool.
d. Verified the successful connection in the Wazuh Dashboard.

Evidence: 
<img width="1366" height="603" alt="active agents 1" src="https://github.com/user-attachments/assets/a1420272-03be-4a35-873c-fed354bb4a5e" />

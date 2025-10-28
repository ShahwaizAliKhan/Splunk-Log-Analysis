<h2>🧠 DNS Log Analysis using Splunk</h2>

<p>This project focuses on analyzing DNS logs using Splunk to detect anomalies, failed lookups, and suspicious network behavior. Below are the key steps performed during the analysis process.</p>

<hr>

<h3>🔹 Field Extraction</h3>
<p>Extracted important fields such as timestamp, source IP, destination IP, protocol, query, and response code using Splunk’s field extraction feature.</p>
<p><i>Screenshot:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-22%20143552.png?raw=true" alt="Field Extraction Screenshot" width="700">
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-22%20143921.png?raw=true" alt="Field Extraction Screenshot" width="700">
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-22%20144044.png?raw=true" alt="Field Extraction Screenshot" width="700">
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-22%20144204.png?raw=true" alt="Field Extraction Screenshot" width="700">
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-22%20144433.png?raw=true" alt="Field Extraction Screenshot" width="700">
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-22%20144626.png?raw=true" alt="Field Extraction Screenshot" width="700">
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20163731.png?raw=true" alt="Field Extraction Screenshot" width="700">

<hr>

<h3>🔹 Basic Log Exploration</h3>
<p>Performed basic searches to explore DNS traffic patterns, top queried domains, and response statistics.</p>
<p><i>Total Log Count:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20190612.png?raw=true" alt="Basic Exploration Screenshot" width="700">

<p><i>Top Queried Domains:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20164134.png?raw=true" alt="Basic Exploration Screenshot" width="700">

<p><i>Top Requesting Hosts:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20164227.png?raw=true" alt="Basic Exploration Screenshot" width="700">

<p><i>Response Type Summery:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20164319.png?raw=true" alt="Basic Exploration Screenshot" width="700">

<hr>

<h3>🔹 Security-Focused Analysis</h3>
<p>Conducted in-depth searches to detect anomalies such as failed lookups (NXDOMAIN), suspicious record types, and potential domain generation algorithm (DGA) activity.</p>
<p><i>Find Failed DNS Queries (NXDOMAIN):</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20173546.png?raw=true" alt="Security Analysis Screenshot" width="700">

<p><i>Identifying Suspicious Record Types (TXT, NULL, SRV):</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20173927.png?raw=true" alt="Security Analysis Screenshot" width="700">

<p><i>High Frequency Queries (DGA Detection):</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20174202.png?raw=true" alt="Security Analysis Screenshot" width="700">

<p><i>Cross-Checking Internal to External Requests:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20174356.png?raw=true" alt="Security Analysis Screenshot" width="700">

<hr>

<h3>🔹 Visualization Dashboards</h3>
<p>Created Splunk dashboards to visualize DNS activity, including top queried domains, source IPs, and response code distribution.</p>
<p><i>Top Queried Domains:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20182826.png?raw=true" alt="Dashboard Screenshot" width="700">

<p><i>Top Source IPs:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20182839.png?raw=true" alt="Dashboard Screenshot" width="700">

<p><i>Response Code Breakdown:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20182851.png?raw=true" alt="Dashboard Screenshot" width="700">

<p><i>Suspicious Query:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20182902.png?raw=true" alt="Dashboard Screenshot" width="700">

<hr>

<h3>🔹 Threat Detection Alerts</h3>
<p>Configured Splunk alerts to automatically detect abnormal DNS behavior, such as repeated NXDOMAIN responses or unusual record types.</p>
<p><i>Screenshot:</i></p>
<img src="https://github.com/ShahwaizAliKhan/Splunk-Log-Analysis/blob/main/DNS%20log%20analysis/Screenshot%202025-10-24%20182736.png?raw=true" alt="Alert Screenshot" width="700">

<hr>

<h3>✅ Final Outcome</h3>
<p>This DNS log analysis helped me identify unusual domain activity and improve visibility into network-level threats using Splunk dashboards and alerts.</p>

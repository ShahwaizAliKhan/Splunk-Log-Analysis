<h2>🧠 DNS Log Analysis using Splunk</h2>

<p>This project focuses on analyzing DNS logs using Splunk to detect anomalies, failed lookups, and suspicious network behavior. Below are the key steps performed during the analysis process.</p>

<hr>

<h3>🔹 Step 1: Field Extraction</h3>
<p>Extracted important fields such as timestamp, source IP, destination IP, protocol, query, and response code using Splunk’s field extraction feature.</p>
<p><i>Screenshot:</i></p>
<img src="images/step2_field_extraction.png" alt="Field Extraction Screenshot" width="700">

<hr>

<h3>🔹 Step 3: Basic Log Exploration</h3>
<p>Performed basic searches to explore DNS traffic patterns, top queried domains, and response statistics.</p>
<p><i>Screenshot:</i></p>
<img src="images/step3_basic_exploration.png" alt="Basic Exploration Screenshot" width="700">

<hr>

<h3>🔹 Step 4: Security-Focused Analysis</h3>
<p>Conducted in-depth searches to detect anomalies such as failed lookups (NXDOMAIN), suspicious record types, and potential domain generation algorithm (DGA) activity.</p>
<p><i>Screenshot:</i></p>
<img src="images/step4_security_analysis.png" alt="Security Analysis Screenshot" width="700">

<hr>

<h3>🔹 Step 5: Visualization Dashboards</h3>
<p>Created Splunk dashboards to visualize DNS activity, including top queried domains, source IPs, and response code distribution.</p>
<p><i>Screenshot:</i></p>
<img src="images/step5_dashboard.png" alt="Dashboard Screenshot" width="700">

<hr>

<h3>🔹 Step 6: Threat Detection Alerts</h3>
<p>Configured Splunk alerts to automatically detect abnormal DNS behavior, such as repeated NXDOMAIN responses or unusual record types.</p>
<p><i>Screenshot:</i></p>
<img src="images/step6_alerts.png" alt="Alert Screenshot" width="700">

<hr>

<h3>✅ Final Outcome</h3>
<p>This DNS log analysis helped identify unusual domain activity and improve visibility into network-level threats using Splunk dashboards and alerts.</p>

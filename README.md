# Systen-monitoring
Dashboard monitoring system

Project Title: System Health Dashboard for Personal Computer Monitoring

A Self-hosted, real-time system monitoring dashboard built with Python and Html that tracks CPU, memory, disk usage and uptime on any device. 

Objective 
In modern personal computing, monitoring system performance is essential to ensure stability and efficiency. Our objective was to create a lightweight, browser-accessible dashboard that displays live hardware stats for a computer using open-source Python tools without the need for external cloud services or installations.

Tools & Technologies Used 
Python – Core programming language 
Psutil – Python library to retrieve system performance data
HTML + CSS – User interface design 

System Flow & Architecture
•	Python’s psutil collects data such as CPU usage, memory usage, disk space and system uptime.
•	Data is rendered on a web dashboard (index.html) that auto-refreshes every 5 seconds.
•	Users can view the dashboard at http://localhost:5000 or from any browser on the same network.
Key Features & Code Highlights 
•	Real-time metrics: CPU, RAM, Disk and updated uptime every few seconds
•	Auto-refreshing dashboard: Clean and simple HTM/CSS interface
•	Cross-platform: Works on Windows, macOS, Linux
•	Lightweight: No database, fast local hosting



Cost Effectiveness
Traditional Monitoring services: 
	Average cost: $20-$50/month per device 
	For 1,000 devices:
	$20,000 to $50,000/month
	That’s $240,000 to $600,000 per year
Our System Monitoring Dashboard: 
	Built with open-source tools: $0 software cost
	Hosted on 1-2 Raspberry Pi or internal server 
	Estimated electricity/network usage: < $10/month
	Annual cost: under $500

 



Future Improvements
Store historical metrics in SQLite for graph generation 
Add authentication and role-based access for shared networks

Conclusion
This Project successfully delivers a local self-hosted system monitoring dashboard using Python and HTML. It runs on any computer and provides real-time insights into system performance, helping users proactively monitor their system health without relying on third-party software. The simplicity and extensibility of the project make it suitable for both personal, educational and big companies. 



Developers: Chuka, Luis, Ankur, Sean and Eddie 





Any Questions? 




IT Support bootcamp training plan - biweekly sessions

Topics in addition to Google IT Support Fundamentals
- Network apps, client-server(two-tier),FE-BE-DB three tier architecture, microservices, sync-vs-async EDA, scaleble HA/HL apps architectures, SPOF, LoadBalancing, Reverse Proxies

- Network ISO/OSI, DNS, HTPP/S
  
- Chrome browser Developers Tools

- Incident Management

- Web-apps Troubleshooting workflow

- Web-Application setup & HTTP/S Error codes

-  REST API

- NewRelic foundations

- OpsGenie foundations (Alert runbooks, PostMortems, Escalation)

- Windows/Linux CLI tooling (basic scripting)

- docker, container images, instances, docker compose https://docs.docker.com/get-started/

- k8s/AKS intro


------
Biweekly Session Plan

| Date | Session Topic |
| :---: |  :---: | 
| August 1st | Session 0: Network/web apps application architectures|
| August 3rd | Session 1: Network ISO/OSI Layers |
| August 8th | Session 2: IPv4 Addressing and TCP/IP |
| August 10th| Session 3: Sockets, DNS, and HTTP/S|
| August 14th | Session 4: FTP, SSH, and RDP |
| August 15th | Session 5: Network/service/Web-Apps Troubleshooting Workflow |
| August 17th | Session 6: Web-Application Setup & HTTP/S Error Codes|
| August 22nd | Session 7: REST API|
| August 24th | Session 8: Chrome Browser Developer Tools, Google Network tools, VPNs,  Postman|
| August 29th | Session 9: Windows/Linux CLI Tooling and Basic Scripting|
| August 31st | Session 10: Incident and Problem Management with ServiceNow, SRE approach|
| September 5th | Session 11: Monitoring Fundamentals and NewRelic Foundations|
| September 7th | Session 12: Logs, Metrics, Traces, and Dashboards|
| September 12th | Session 13: OpsGenie Foundations (Alert Runbooks, PostMortems, Escalation)|
| Date: September 14th| Session 14: App Support/SRE Interview Questions|


---------

Homework assignments for each topic in the 2.5-month training plan:
Session 0: Research which app/service architecture have following web-services: Atlassian Jira/Conflunece, SAP ERP, SalesForce Commerce Cloud/e-commerce webstores, LinkedIn, Netflix, Facebook, Flickr, your favorite mobile app, Google search engine.
Put your findings into the table: Service Name, Architecture Type, Numbers of users, Client type, Is service Global or Local?, DB type(s), Sync or Async?

Session 1: Network ISO/OSI Layers
Research and summarize the purpose and function of each layer in the OSI model.
Create a diagram illustrating the encapsulation/de-encapsulation process at each layer when you open web page from your own PC/mobile phone. 
Identify and explain the headers used at different layers.
Find in google services that still use TCP:80 port and try to telnet into that HTTP server's IP address. Try to issue HELLO, GET index.html commands interactively from telnet console.


Session 2: IPv4 Addressing and TCP/IP

Practice subnetting exercises to understand IPv4 addressing and subnet masks.
Investigate and compare the differences between TCP and UDP protocols.
Research and explain the purpose of TCP/IP headers.
Learn CIDR, RFC1918, APIPA. Install Cisco Packet Tracer, create simple Network, look at the packet flow when browser sends request to web-service.

Session 3: TCP/IP Sockets, DNS, and HTTP/S
Install Wireshark/tcpdump on your own PC.
Watch youtube intro to the tool. Start capturing your home traffic. What kind of packets do you see in your WiFi, LAN. Collect MAC addressses of the nodes in your lan, put them into the table and identify your PC's, Router's LAN port, mobile phone's MAC-addresses.

Run capture session with tools like Wireshark/tcpdump when browser opens wwww.google.com. What happens? What stages do you see in your capture.
Investigate the DNS resolution process and explain how it works. Use -v option with dig.
Clear DNS cache and try resolutuin against 1.1.1.1, 8.8.8.8, and other public DNS services.

Analyze and compare the differences between HTTP and HTTPS protocols.

Session 4: FTP, SSH, and RDP

Set up an FTP server and demonstrate file transfer using an FTP client.
Practice connecting to a remote server using SSH and perform basic commands.
Explore the functionalities and usage of Remote Desktop Protocol (RDP).
What ports need to be open on remote system's firewall for SSH and RDP to work? Which transport layer protocols are used by SSH, RDP?

Session 5: Web-Apps Troubleshooting Workflow
Analyze a given web application and create a step-by-step troubleshooting workflow.
Research common issues that occur in web applications and provide possible solutions.
Practice using debugging tools to identify and resolve issues in a web application.

Session 6: Web-Application Setup & HTTP/S Error Codes

Set up a local web application server and configure a sample application.
Experiment with different HTTP status codes and understand their meanings.
Identify and document common HTTP/S error codes and their troubleshooting steps.
Create table with common Error codes - 1xx, 200, 3xx, 4xx, 5xx  (Group them by their occurence - client side, server side)
Think on reason each error occurs? Which Error Codes would you like to monitor on production system, why?
Session 7: REST API

Design and implement a simple REST API using a programming language of your choice.
Explore different API authentication methods (e.g., API keys, OAuth) and their advantages.
Investigate best practices for API versioning, documentation, and error handling.
Session 8: Chrome Browser Developer Tools

Explore the various tools available in Chrome Developer Tools and their use cases.
Use the Network panel to analyze the requests and responses of a web page.
Experiment with the Console panel to execute JavaScript commands and debug issues.
Session 9: Windows/Linux CLI Tooling and Basic Scripting

Practice using common command-line tools in Windows and Linux environments.
Write a script that automates a repetitive task using shell scripting or PowerShell.
Research and implement different control structures (loops, conditionals) in your script.
Session 10: Incident and Problem Management with ServiceNow

Explore the features and capabilities of ServiceNow for incident and problem management.
Create an incident management workflow and document the steps involved.
Investigate the role of Service Level Agreements (SLAs) and how they are used in incident management.
Session 11: Monitoring Fundamentals and NewRelic Foundations

Research different monitoring techniques and tools used in IT operations.
Set up a basic monitoring system using NewRelic or a similar tool.
Configure alerts and notifications based on specific metrics or events.
Session 12: Logs, Metrics, Traces, and Dashboards

Understand the differences between logs, metrics, and traces in a monitoring context.
Configure log collection and analysis using a tool such as Elasticsearch, Logstash, and Kibana (ELK).
Create a custom dashboard in your monitoring tool to visualize important metrics.
Session 13: OpsGenie Foundations (Alert Runbooks, PostMortems, Escalation)

Familiarize yourself with the features and workflows in OpsGenie for alert management.
Create an alert runbook for a specific scenario, outlining the necessary steps to resolve the issue.
Research incident postmortems and document the key components and best practices.
For the remaining sessions, you can continue to explore and deepen your understanding of each topic by researching relevant articles, tutorials, and real-world examples. Additionally, you could consider implementing small projects or exercises related to each subject to reinforce your learning. Remember to practice hands-on activities and seek out opportunities to apply your knowledge in practical situations.

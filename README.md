# SOAR-EDR-Project
# Project Objective
This project demonstrates the integration of Security Orchestration, Automation, and Response (SOAR) with Endpoint Detection and Response (EDR) to streamline security workflows and improve overall cybersecurity defenses. Leveraging LimaCharlie for EDR and Tines for SOAR, the project delivers real-time security insights and automates responses, particularly focusing on detecting and addressing credential access attacks using the LaZagne tool.

LimaCharlie identifies LaZagne's activity on endpoint devices, triggering automatic alerts and remediation actions, while allowing users to decide whether to isolate compromised machines. Communication channels, including Slack and email, are used to ensure timely notifications and responses, making security operations more flexible and responsive.

# Tools Used
- <b>Windows Machine</b>: Target machine LimaCharlie will detect for isolation decision, where users can choose to isolate it based on the threat severity.
- <b> LimaCharlie (EDR)</b>: Used to detect and respond to security threats.
- <b>Tines (SOAR)</b>: Automates the security workflows and orchestrates the response actions.
- <b>Slack</b>: Serves as the communication platform to receive alert detections.
- <b>ProtonMail (Email)</b>: Used to receive detection alert emails.
- <b>VirtualBox</b>: For hosting the virtual machine used in the project. (You can use other cloud providers or use Vmware, just make sure they are connected to the internet)

# Skills Gained 
- Integration of SOAR and EDR Tools: Developed expertise in integrating SOAR tools with EDR platforms to enhance automated incident response capabilities.
- Automation of Security Workflows: Gained proficiency in designing and implementing automated security workflows for real-time detection, response, and notification, streamlining incident management processes.
- Threat Detection and Response: Acquired hands-on experience in configuring and utilizing LimaCharlie for detecting threats on compromised endpoints, including making decisions on whether to isolate affected systems based on threat assessments.
- Communication and Alerting Systems: Enhanced abilities in setting up and managing communication and alerting mechanisms via Slack and email, ensuring critical security information is shared promptly and effectively.
- User Prompt Configuration: Learned to create and configure interactive user prompts within SOAR workflows, facilitating decision-making during incident response.
- Incident Response Management: Strengthened incident response management skills by coordinating responses across multiple tools and platforms, ensuring efficient and unified handling of security incidents.

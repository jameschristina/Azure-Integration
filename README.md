<h1>Zero-Trust Merged Topology - Azure SaaS/PaaS Implementation </h1>

<h2>Description</h2>
This project entailed merging network topologies for 2 companies undergoing merger and acquisition (M&A). Executives of the newly merged company expressed interest in cloud integration.
<br >

<br />

I designed topology around the following preexisting components that were required for the project:

• Zero-Trust Principles: Implement strict identity verification, assume breach (never trust, always verify), and apply micro-segmentation. Every user and device must authenticate access resources, regardless of their location.  

• Hybrid Infrastructure: Integrate both on-premises data centers and cloud services (e.g., Microsoft Azure or AWS).  

• Network Segmentation: Separate the networks using Next-Generation Firewalls (NGFW) to isolate traffic between the two merged companies (e.g., VLANs for Finance vs. HR/Healthcare).  

• Secure Remote Access: Incorporate a robust VPN (like an IPSec or SSL VPN) with Multi-Factor Authentication (MFA) for telecommuters. 

• Budget Constraint: Stay within the stated budget (usually $50,000) for hardware, software, and cloud implementation. 
<br >
<br />
For AD/on-prem server migration to cloud, Azure SaaS was implemented to work with active directory (AD) and domain services enabling cloud elasticity meaning services can be added, changed, and removed as necessary based on volume. Azure PaaS was put in place to allow for creation of a dev pipeline, and gateway access to applications, databases and storage.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Azure</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Linux</b>

<h2>Preview:</h2>

<p align="center">
<br/>
<img src="https://i.imgur.com/4acnU6x.png" height="80%" width="80%" alt=""/>
<br />
<br />



</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>


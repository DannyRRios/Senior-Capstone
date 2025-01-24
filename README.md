<h1>My Senior Capstone - Enterprise Information Security Program Plan</h1>


<h2>Description</h2>

- <b>Part One</b>
  - For my senior project, two other team members and I were required to create an Enterprise Information Security Program Plan for a small college that contained elements of the Payment Card Industry Data Security Standard (PCI DSS), FERPA, HIPAA, Non-Disclosure (Proprietary) Information, and other undetermined Personally Identifiable Information (PII). Within the Enterprise Information Security Program Plan there was many other plans included which were but not limited to an Enterprise Data Classification Plan, Asset Management Plan, Enterprise Risk Management Plan, Enterprise Technology Usage Plan, Incident Response Plan, Acceptable Use Policy, Configuration and Change Management Plan, and a Secure Configuration Plan. 
- <b>Part Two</b>
  - For the second half of this project we were required to put everything that we had planned into action and create a fully functional environment in Microsoft Azure, which had to be properly secured and meet all necessary standards for the small college’s needs.  A penetration testing team was then brought in, and we had to remediate any flaws in our system that were exploited. The following is what we were given as an outline to complete:
    - a)	Hosted on AWS or Azure platform
    - b)	A routed and switched environment that
      -   a.	Locks down unauthorized domains
      -   b.	Locks down unauthorized IP Ranges
      -   c.	Locks down unauthorized port ranges
      -   d.	Locks down unauthorized programs
      -   e.	Allows for third party agreements
      -   f.	Uses VLANS for management
      -   g.	Uses VPNs as appropriate for confidentiality
    - c)	Windows 2016/2019 and Linux servers (must contain 2 flavors or more) and must contain:
      - a.	DNS (trusted DNS or secure DNS)
      - b.	DHCP (used to assign 
      - c.	NTP (trusted servers)
      - d.	A database (SQL or Oracle)(I always say go with SQL for the shorter periods)
      - e.	Certificate based privacy (minimum)
    - d)	IPS/IDS system that reports to a working SIEM (Currently Splunk or Rapid 7)
      - a.	Network based
      - b.	Endpoint based
      - a.	Tiered Collectors (collects and aggregates data for processing)
      - c.	Normalization
      - d.	Working parse (does not have to be tuned during initial onset – even though the working perimeter will reduce much of the overhead traffic)
    - e)	Data inspection (inbound/outbound traffic, inbound infected files, and outbound data exfiltration) for categorized data and malicious activity 
    - f)	Scanning (vulnerability – can be OpenVAS, InsightIDR, or other common usage scanning mechanism)
    - g)	An Active backup strategy (must comply with best practices for backup programs)
    - h)	Unauthorized change detection
    - i)	Reporting of unauthorized usage

<br />

<h2>I have attached the final project plan to this repository and have redacted my team members names for confidential reasons</h2>

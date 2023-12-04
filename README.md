<h1 align="center">Explore Signatures and Logs with Suricata</h1>

<h2 align="center">Project Description</h2>

<p align="center">You’re a security analyst who must monitor traffic on your employer's network. You’ll be required to configure Suricata and use it to trigger alerts.</p>

<h3 align="center">Task 1 - Examine a Custom Rule in Suricata</h3>

<p align="center"><img src="https://github.com/GeoffreyMorren/Suricata/assets/152500568/3cfc3120-2748-4fda-8476-f16d5dc6290f" alt="Task 1 Image"></p>

<p align="center">This signature triggers an alert whenever Suricata observes the text GET as the HTTP method in an HTTP packet from the home network going to the external network.</p>

<h3 align="center">Task 2 - Trigger a Custom Rule in Suricata</h3>

<p align="center"><img src="https://github.com/GeoffreyMorren/Suricata/assets/152500568/5d7ab5d7-cf05-401a-af42-cf1544e5c7ed" alt="Task 2 Image"></p>

<p align="center">The -r sample.pcap option specifies an input file to mimic network traffic. In this case, the sample.pcap file.</p>
<p align="center">The -S custom.rules option instructs Suricata to use the rules defined in the custom.rules file.</p>
<p align="center">The -k none option instructs Suricata to disable all checksum checks.</p>

<h3 align="center">Task 3 - Examine eve.json Output</h3>

<p align="center"><img src="https://github.com/GeoffreyMorren/Suricata/assets/152500568/cea94bab-a3f1-41d2-8d94-48515d2b01ce" alt="Task 3 Image"></p>

<p align="center">Using the “jq” command to display entries in an improved format.</p>

<p align="center"><img src="https://github.com/GeoffreyMorren/Suricata/assets/152500568/39d312a6-51e9-48e1-9f72-96bbc275c2f6" alt="Task 3 Image"></p>

<p align="center">Using the “jq” command to extract the fields specified in the list in the square brackets from the JSON payload.</p>

<p align="center"><img src="https://github.com/GeoffreyMorren/Suricata/assets/152500568/52402502-1613-49eb-a9b6-6c1780fe821c" alt="Task 3 Image"></p>

<p align="center">Using the jq command to display all event logs related to a specific flow_id from the eve.json file.</p>

<h2 align="center">Summary</h2>

<p align="center">With this exercise, I was able to get practical experience in Suricata to create custom rules and run them in Suricata. As well as monitor traffic captured in a packet capture file and examine the fast.log and eve.json output.</p>

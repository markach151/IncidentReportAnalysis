**Use the NIST Cybersecurity Framework to respond to a security incident**


**Description**

In this scenario, I'm a cybersecurity analyst working for a multimedia company. My organization recently experienced a DDoS attack, which compromised the internal networks for two hours until it was resolved. I analyzed the situation using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF) and created an incident report. 

<table>
  <tr>
   <td><strong>Summary</strong>
   </td>
   <td colspan="3" >The organization experienced a distributed denial of service (DDoS) attack through a flood of ICMP packets which compromised the internal network. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets and halting all non-critical network services, so that critical network services c could be restored.    
   </td>
  </tr>
  <tr>
   <td>Identify
   </td>
   <td colspan="3" >A malicious actor targeted the company by sending a flood of ICMP pings into the internal network through an unconfigured firewall. The entire internal network was compromised for two hours. All critical network services needed to be restored.  
   </td>
  </tr>
  <tr>
   <td>Protect
   </td>
   <td colspan="3" >The network security team implemented a new firewall rule to limit the rate of incoming ICMP packets and an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics. 
   </td>
  </tr>
  <tr>
   <td>Detect
   </td>
   <td colspan="3" >The network security team implemented source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets and network monitoring software to detect abnormal traffic patterns. 
   </td>
  </tr>
  <tr>
   <td>Respond
   </td>
   <td colspan="3" >In the case of a future security incident, the incident management team would first respond by isolating the affected systems to prevent further spread throughout the network. They will attempt to restore critical network services as quickly as possible. Then the cybersecurity team will investigate by analyzing network logs and detection systems for abnormal behavior. All future security events will be reported to upper management and necessary legal authorities. 
   </td>
  </tr>
  <tr>
   <td>Recover
   </td>
   <td colspan="3" >To recover from a DDoS attack due to ICMP flooding, access to the company’s network services need to be restored to a normal functioning state. Now with the new firewall rule, ICMP packet flooding will be blocked. All non-critical network services are brought offline while critical network services are restored. Finally, once the flood of ICMP packets have timed out, all non-critical network systems and services can be brought back online.    
   </td>
  </tr>
</table>

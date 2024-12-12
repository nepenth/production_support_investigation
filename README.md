# Production Support Team Conversation Guide

## **1. Introduction**
### **Purpose**  
We’re here to better understand your production support operations to identify patterns, areas for improvement, and opportunities for automation. This will help reduce incident frequency, manual effort, and ultimately improve our system reliability and efficiency.

### **Objectives**
- Quantify incidents: volume, types, and patterns.
- Identify recurring manual work (toil) and automation opportunities.
- Highlight collaboration areas between SRE and Production Support.

### **Collaboration Reminder**  
This is a partnership to identify solutions that make everyone’s work easier, more efficient, and reduce operational burden.

---

## **2. Incident Metrics and Trends**

### **Key Questions**
1. **Volume**  
   - How many incidents do you handle in a typical week/month?  
   - How many of these incidents are P1/P2 (critical/high-priority)?  

2. **Type**  
   - What are the most common incident types? (e.g., latency, errors, resource exhaustion, outages, failed deployments).  
   - Are there recurring patterns or specific failure domains?  

3. **Repeat Incidents**  
   - How often do the same incidents or failures occur?  
   - What are the common contributing factors? (e.g., misconfigurations, manual errors, insufficient monitoring).  

4. **Resolution Time**  
   - What is the average time to detect, diagnose, and resolve an incident (MTTD, MTTR)?  
   - Where do you face delays? (e.g., lack of tooling, unclear ownership, upstream dependencies).  

### **Actionable Insights**
- Document **incident frequency, impact, and patterns**.
- Flag **high-repeat incidents** as prime candidates for deeper analysis and automation.

---

## **3. Manual Effort and Toil**

### **Definition of Toil**
Toil = Any manual, repetitive work that could be automated but isn’t yet.

### **Key Questions**
1. **Recurring Manual Tasks**  
   - What tasks do you perform manually during incident resolution?  
   - Are there specific scripts, tools, or dashboards you rely on?  
   - How much of your time is spent “firefighting” versus proactive work?  

2. **Automation**  
   - Do you have any existing automation in place?  
     - For example: auto-recovery scripts, log analysis tools, monitoring alerts.  
   - What tasks do you think could be automated but aren’t?  

3. **Handoffs and Upstream Collaboration**  
   - How often do you need to escalate incidents to the SRE teams?  
   - What are the pain points in that escalation process?  
   - Do you have clear runbooks and automation scripts provided by SRE teams?  

### **Actionable Insights**
- Identify **toil-prone areas** for automation.  
- Highlight **manual tasks with high frequency** or time consumption.  
- Look for **tooling gaps** or missing runbooks.

---

## **4. Engineering Work Required**

### **Key Questions**
1. **Incident Complexity**  
   - How many incidents require code changes, configuration updates, or architectural fixes?  
   - How often do you see issues caused by application bugs versus infrastructure problems?  

2. **Engineering Involvement**  
   - How often do you need to involve development/SRE teams for engineering fixes?  
   - Is there a clear process for transferring ownership of complex issues?  

3. **Root Cause Analysis**  
   - How effective are postmortems in driving engineering improvements?  
   - Are fixes prioritized to prevent recurrence?  

### **Actionable Insights**
- Quantify **engineering-dependent incidents** and their resolution time.  
- Identify opportunities for improving **handoffs** and **root cause fixes**.

---

## **5. Observability and Monitoring Gaps**

### **Key Questions**
1. **Tooling**  
   - What monitoring tools do you rely on to detect and diagnose incidents?  
   - Are there gaps in monitoring coverage or alerting?  

2. **Noise vs. Signal**  
   - How many alerts are actionable versus false positives?  
   - Do you spend time triaging noisy alerts?  

3. **Visibility**  
   - Do you have visibility into upstream SRE monitoring and dashboards?  
   - Is there alignment on SLIs/SLOs with the SRE team?  

### **Actionable Insights**
- Identify **monitoring blind spots** and alert noise.  
- Highlight areas where **SRE teams can improve shared visibility**.

---

## **6. Next Steps and Follow-Up Actions**

### **Quick Wins**
- Highlight obvious areas for **automation** (e.g., auto-recovery for common incidents).  
- Document the **top toil tasks** that can be addressed quickly.

### **Action Items**
- Schedule deeper dives into **high-repeat incidents** and problematic areas.  
- Review existing **runbooks and monitoring coverage** with SRE teams.  
- Develop a plan for implementing **automation** and reducing manual toil.  

### **Follow-Up**
- Agree on a follow-up meeting to review progress and share updates.  
- Document clear ownership for each identified improvement area.  

### **Reiterate the Goal**  
Our aim is to reduce incidents, eliminate repetitive manual work, and free up your time for proactive, higher-value activities. Let’s work together to achieve that.

---

**End of Guide**

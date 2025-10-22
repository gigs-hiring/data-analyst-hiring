Slack Message

---

Hey connectivity team 👋, please find a summary of the requested analysis **analysing usage patterns across our plan offerings.**

1. **How much data does a subscription typically consume?**
    - Avg. Monthly consumption varies significantly across organisations
    - On average usage is higher for SmartDevices(3.2GB) than ACME (1.1GB)
    
    ![image.png](documentation_slack_message_images/image.png)
    

1. **Does usage differ across plans?**
    - On a plan split, we actually see higher usage for ACME compared with SmartDevices
    - Given the huge number of 1GB ACME users, they pull down the overall average, compared with SmartDevices
    
    ![image.png](documentation_slack_message_images/image%201.png)
    
2. **Do subscriptions consume consistent amounts of data throughout their lifetime?**
    - Stable consumption across the **5GB plan**, whilst decreasing for **1GB & Unlimited** plans

![image.png](documentation_slack_message_images/image%202.png)

4. **Retention Rate for recent API Product Launch (People Mobile)**
- Given that **People Mobile** was onboarded very recently, we only have 1 complete month of cohort data (April Subscription Cohort)
- We therefore calculate M1 Retention (D30-60), and compare it with other New Subscriptions from the April Cohort
- Retention is significantly lower (***16%***) compared to ***Connect (ACME): Phones (34.6%)*** and ***Connect (Smart Devices): Wearables (54%)***

![image.png](documentation_slack_message_images/image%203.png)

#### Initial Recommendations & Next Steps
---

**Connectivity Team**
1. **Updated plan offering**: Consider replacing 5GB plan with 3GB Plan: 
- Most 5GB subscriptions consume ~2GB of data per month
- **3GB Plan** would suffice most users, migrating the remaining towards **Unlimited**
2. **Proactive Upsell:** Identify subscriptions exceeding 90% of allowance in consecutive periods and nudge them to the next plan before renewal


**API Launch @HeadOfProduct**
- Let’s keep a close eye on this 👁️ and review the next completed cohorts
- Although the API product is very different than the Connect service, we need to identify opportunities to improve retention.
    - Improve our API documentation
    - Collect API needs of PeopleMobile and add features to the API

**You can find the complete analysis here: [Insert Link] Please let me know if you have any questions! 🙏**
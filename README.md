# Hotel Booking Demand Analysis

# Dashboard 1: Executive Overview – Strategic Business Report

This dashboard serves as the high-level diagnostic tool for the hotel's health. It tracks where guests come from, when they book, and which categories are driving the **$13.12M** in revenue leakage.

---
<p align="center">
  <img src="tableau/dashboard/DASHBOARD 1_ EXECUTIVE OVERVIEW.png"
       alt="Dashboard 1"
       width="1000"
       height="800>
</p>

## Key Performance Indicators (KPIs)

| KPI | Value | Analysis | Strategy |
|:---|:---:|:---|:---|
| **Total Bookings** | **119,390** | High volume, but high noise. **37%** of these never materialize. | Shift **5%** of TA bookings to Direct to save commission fees. |
| **Total Guests** | **234,988** | Massive footfall; drives all variable operational costs. | Implement **Family F&B Bundles** to increase spend-per-head. |
| **Cancellation Rate** | **37.04%** | **Critical Red Flag** — high inventory uncertainty. | Use data-driven overbooking ratios to hit **100% capacity**. |

---

# Detailed Chart Analysis & Strategy

## 1. Country Distribution  
**Focus:** Identifying market volatility and geographical revenue leakage.

| Country | Cancel Rate | Revenue Realized | Revenue Lost |
|:---|---:|---:|---:|
| **Portugal (PRT)** | **56.64%** | $9.04 Million | **$5.09 Million** |
| **Spain (ESP)** | 25.41% | $2.28 Million | $1.02 Million |
| **UK (GBR)** | 20.22% | $4.15 Million | $1.13 Million |
| **France (FRA)** | 18.57% | $3.10 Million | $0.93 Million |
| **Germany (DEU)** | **16.71%** | $2.07 Million | $0.56 Million |

### Strategy to Increase Revenue
Reallocate marketing spend toward **Germany and France**. These markets have the highest *Success-to-Booking* ratio, ensuring every marketing dollar spent actually results in a stay.

### Strategy to Decrease Cancellation
Implement **mandatory prepayments** or non-refundable vouchers specifically for the domestic (**PRT**) market, which currently accounts for the bulk of the **$5M** loss.

---

## 2. Monthly Booking Trend  
**Focus:** Seasonal demand and timing risk.

| Month | Cancel Rate | Revenue Realized | Revenue Lost |
|:---|---:|---:|---:|
| **June** | **41.46%** | $3.19 Million | $1.30 Million |
| **April** | **40.80%** | $2.56 Million | $1.14 Million |
| **August** | 37.75% | **$5.05 Million** | $2.89 Million |
| **July** | 37.45% | $4.25 Million | $2.33 Million |
| **January** | 30.48% | $0.86 Million | $0.41 Million |

### Strategy to Increase Revenue
Implement a **Minimum Length of Stay (MLOS)** of **3 nights** during the July/August peak. This maximizes yield when demand is at its highest.

### Strategy to Decrease Cancellation
Target the **June Gap**. Since June has the highest cancellation rate, offer **Early Summer Non-Refundable** discounts to lock in travelers before they switch to competitors.

---

## 3. Hotel Type vs. Cancellation  
**Focus:** Operational volatility between City and Resort segments.

| Hotel Type | Cancel Rate | Revenue Realized | Revenue Lost |
|:---|---:|---:|---:|
| **City Hotel** | **41.73%** | $17.56 Million | $7.72 Million |
| **Resort Hotel** | 27.76% | $12.04 Million | $5.40 Million |

### Strategy to Increase Revenue
For City Hotels, introduce **Corporate Lock-in Rates**. Partner with businesses to offer lower rates in exchange for contractually guaranteed non-refundable nights.

### Strategy to Decrease Cancellation
City Hotels should safely **overbook by 15–20%**. Since **41.7%** will cancel, overbooking protects the bottom line from empty rooms.

---

## 4. Customer Type Distribution  
**Focus:** Reliability of different booking segments.

| Customer Type | Cancel Rate | Revenue Realized | Revenue Lost |
|:---|---:|---:|---:|
| **Transient** | **40.75%** | $22.70 Million | **$11.50 Million** |
| **Transient-Party** | 25.43% | $5.23 Million | $1.32 Million |
| **Contract** | 30.96% | $1.56 Million | $0.28 Million |
| **Group** | **10.23%** | $0.12 Million | $0.01 Million |

### Strategy to Increase Revenue
Incentivize **Transient-Party** bookings. Offer a free breakfast or spa voucher for guests booking more than one room; these guests cancel far less often than standard transient bookings.

### Strategy to Decrease Cancellation
Pivot toward the **Group** segment. While they currently contribute less revenue, their **10%** cancellation rate is the most stable in the business. Shift sales focus to **MICE (Meetings, Incentives, Conferences, Exhibitions)**.

---

# Final Executive Action Plan

| Priority | Action |
|:---|:---|
| **1** | **Stop the Domestic Leak:** Fix the **$5.09M** loss in Portugal with stricter deposit rules. |
| **2** | **Overbook City Hotels:** Use the **41.7%** cancel rate as a buffer to sell more rooms. |
| **3** | **Prioritize Stability:** Shift marketing from **Transient (40% risk)** to **Group** and **Transient-Party (10–25% risk)**. |
| **4** | **Summer Protection:** Use **MLOS** and non-refundable rates for the **June–August** window to secure high-revenue months. |

---




# Dashboard 2: Revenue & Financial Performance – Strategic Analysis

This dashboard focuses on the financial health of the hotel, tracking how pricing strategies (ADR) and deposit policies directly impact the bottom line. It identifies **Revenue Leakage** and provides a roadmap for yield optimization.

---
<p align="center">
  <img src="tableau/dashboard/Dashboard 2 REVENUE & FINANCIAL PERFORMANCE.png"
       alt="Dashboard 2"
       width="1000">
</p>

## Key Performance Indicators (KPIs)

| KPI | Value | Analysis | Strategic Action |
|:---|:---:|:---|:---|
| **Total Revenue** | **$42.72 Million** | Maximum potential gross value of all bookings. | Baseline for measuring recovery efficiency. |
| **Revenue Realized** | **$29.60 Million** | Actual cash collected from stays and non-refundable fees. | Aim to increase by 15% through policy shifts. |
| **Revenue Loss** | **$13.12 Million** | **Critical Leakage** from refundable cancellations. | Recover $3M by tightening "No Deposit" rules. |
| **Avg. ADR** | **$101.83** | Average daily income earned per occupied room. | Optimize to $115 during peak summer weeks. |

---

# Detailed Chart Analysis & Strategy

## 1. ADR vs. Cancellation (Price Sensitivity)
**Focus:** Analyzing whether higher-priced bookings are more likely to cancel.

| Booking Status | Avg. ADR | Revenue Realized | Revenue Lost |
|:---|---:|---:|---:|
| **Checked-Out (Success)** | $99.99 | $25.99 Million | $0 |
| **Canceled (Loss)** | **$104.96** | $3.61 Million | **$13.12 Million** |

### Insight
Canceled bookings have a **higher ADR ($104.96)** than successful bookings. This indicates guests may be price-shopping after booking and canceling when lower alternatives are found.

### Strategy to Increase Revenue
Offer an **Instant Value Add** (free premium Wi-Fi or minibar credit) for bookings with ADR above **$110** to improve commitment.

### Strategy to Decrease Cancellation
Implement a **Price Match Guarantee** for direct bookings to prevent high-value cancellations and re-booking elsewhere.

---

## 2. Deposit Type Impact (The Commitment Factor)
**Focus:** Evaluating how upfront financial commitment influences guest arrival.

| Deposit Type | Success Rate | Revenue Realized | Revenue Lost |
|:---|---:|---:|---:|
| **Non Refund** | **99.36%** | $3.62 Million | $0 |
| **No Deposit** | 71.62% | $25.95 Million | **$13.10 Million** |
| **Refundable** | 77.78% | $0.03 Million | $0.02 Million |

### Insight
**Non-Refundable deposits show near-perfect success rates**, while almost the full **$13.1M** revenue leakage is linked to **No Deposit** reservations.

### Strategy to Increase Revenue
Shift the default booking option to **Non-Refundable**, supported by a **5–10% incentive discount** to secure revenue upfront.

### Strategy to Decrease Cancellation
For **No Deposit** reservations, require a **Credit Card Guarantee** with some penalty for cancellations.

---

## 3. Revenue by Market Segment
**Focus:** Identifying the most profitable and reliable booking channels.

| Segment | Cancel Rate | Revenue Realized | Revenue Lost |
|:---|---:|---:|---:|
| **Online TA** | 36.72% | **$13.73 Million** | **$10.21 Million** |
| **Direct** | **15.34%** | $4.10 Million | $0.99 Million |
| **Groups** | 61.06% | $4.02 Million | $0.65 Million |

### Insight
Online Travel Agents are high-volume but high-risk, driving **$10M** in lost revenue. **Direct bookings** remain the most stable channel.

### Strategy to Increase Revenue
Invest in SEO and metasearch to increase share of **Direct** bookings and improve realized revenue quality.

### Strategy to Decrease Cancellation
For **Groups** bookings, eliminate soft blocks and require a **25% non-refundable deposit** for blocks exceeding five rooms.

---

## 4. ADR Seasonality (Monthly Yield Trend)
**Focus:** Aligning pricing strategies with demand cycles.

| Month | Avg. ADR | Success Rate | Revenue Performance |
|:---|---:|---:|:---|
| **August** | **$140.11** | 62.25% | **Peak Revenue Month** |
| **July** | $126.79 | 62.55% | High Summer Demand |
| **January** | $70.36 | 69.52% | Off-Season Low |

### Insight
ADR peaks in August, but so does inventory pressure. A **37.7% cancellation rate** in August makes revenue leakage especially expensive due to the **$140 ADR**.

### Strategy to Increase Revenue
Apply **Dynamic Pricing Surges**, increasing rates by **10%** for the final **15%** of inventory during July–August.

### Strategy to Decrease Cancellation
Enforce a **7-day cancellation policy** during high-ADR summer months to improve resale opportunities at premium rates.

---

# Final Action Plan

| Priority | Strategic Action |
|:---|:---|
| **1** | **Monetize Commitment:** Use the 99% success rate of Non-Refundables to support aggressive **Pay Now & Save** campaigns. |
| **2** | **Verify High-Value Bookings:** Reservations above **$110 ADR** require mandatory reconfirmation 3 days prior to arrival. |
| **3** | **Optimize Group Deposits:** Reduce 61% volatility in group blocks through stricter upfront payment terms. |
| **4** | **Summer Protection:** Use a **7-day cancellation window** during July–August to protect **$140 room yield**. |

---




# Dashboard 3: Operations & Behavior – Strategic Analysis

This dashboard evaluates operational efficiency and guest behavioral patterns. By analyzing loyalty, lead times, and service requests, opportunities can be identified to improve guest satisfaction while protecting the bottom line.

---
<p align="center">
  <img src="tableau/dashboard/Dashboard 3 OPERATIONS & BEHAVIOR.png"
       alt="Dashboard 3"
       width="1000">
</p>

## Key Performance Indicators (KPIs)

| KPI | Full Form | Value | Analysis |
|:---|:---|:---:|:---|
| **TSR** | Total Special Request | **68,215** | High engagement; guests are actively communicating needs. |
| **TRG** | Total Repeated Guest | **3,810** | Low volume (**3.2%**) but represents the most stable revenue segment. |
| **ALOS** | Avg. Length of Stay | **3.43 Nights** | Typical mix of short-stay business and mid-stay leisure demand. |
| **BCR** | Booking Change Rate | **15.14%** | Indicates high flexibility and volatility after initial booking. |

---

# Detailed Chart Analysis & Strategy

## 1. Repeated Guest Loyalty (The Loyalty Value)
**Focus:** Comparing the reliability of returning guests versus first-time visitors.

| Guest Type | Cancel Rate | Revenue Realized | Revenue Lost |
|:---|---:|---:|---:|
| **Repeated Guest** | **14.49%** | $0.50 Million | $0.08 Million |
| **First-Time Guest** | **37.79%** | $29.10 Million | $13.04 Million |

### Insight
Repeated guests are **2.5x more likely to show up** than first-time guests. Although they represent a small share of volume, they carry the lowest risk of revenue loss.

### Strategy to Increase Revenue
Launch a **Welcome Back Incentive**. Since these guests have a lower ADR (**$64**), offer discounted premium room upgrades at check-in to boost yield without increasing cancellation risk.

### Strategy to Decrease Cancellation
Use automated loyalty recognition so returning guests receive personalized **Welcome Back** experiences, strengthening stay intent.

---

## 2. Room Assignment Discrepancy (Match vs. Mismatch)
**Focus:** Operational accuracy in meeting guest expectations.

| Status | Count | Percentage | Operational Impact |
|:---|---:|---:|:---|
| **Match** | 104,473 | 87.5% | High operational accuracy |
| **Mismatch** | **14,917** | **12.5%** | Potential dissatisfaction or free upgrades |

### Insight
**12.5%** of guests are not receiving the room originally booked, often resulting in complimentary upgrades that erode revenue potential.

### Strategy to Increase Revenue
Implement **Paid Upsell Automation**. Offer mismatch rooms as discounted upgrades **48 hours before arrival**, monetizing inventory that may otherwise be given away.

### Strategy to Decrease Cancellation
For matched reservations, send room-type previews or visuals **3 days before arrival** to reinforce expectation and commitment.

---

## 3. Lead Time Analysis
**Focus:** Advance planning behavior and its impact on booking stability.

### Key Data
- **Average Lead Time:** **104 Days**

### Insight
Guests book over **3 months** in advance. Longer lead times increase the likelihood of plan changes, contributing to the **15% Booking Change Rate**.

### Strategy to Increase Revenue
Implement **Lead-Time Layering** with early-bird non-refundable offers for bookings made **90+ days** in advance to secure base occupancy.

### Strategy to Decrease Cancellation
Use **Milestone Emails** at the **60-day** and **30-day** marks. Guests engaging with these touchpoints are more likely to complete their stay.

---

## 4. Special Requests vs. Engagement
**Focus:** Relationship between guest engagement and stay completion.

### Key Data
- **Total Special Requests:** **68,215**

### Insight
Guests making one or more requests show significantly lower cancellation rates. Engagement is a strong proxy for commitment.

### Strategy to Increase Revenue
Monetize requests through **Add-on Packages**, such as:
- Celebration Kits  
- Early Arrival Guarantee  
- Premium Guest Preference Bundles  

### Strategy to Decrease Cancellation
Prioritize fulfillment of special requests for **No Deposit** bookings. Early responsiveness reduces the chance of losing guests to competitors.

---

# Final Action Plan

| Priority | Strategic Action |
|:---|:---|
| **1** | **Cultivate Loyalty:** Increase TRG from **3.2% to 6%** through post-stay email marketing. |
| **2** | **Monetize Upgrades:** Reduce the **12.5%** mismatch rate by selling those rooms as discounted upgrades. |
| **3** | **Engagement as Security:** Encourage special requests during booking to strengthen stay commitment. |
| **4** | **Lead Time Management:** Use the **104-day** booking window to build guest relationships through automated touchpoints. |

---
# Marketing Analytics & Testing 

---

### **1. What is ROI in marketing and how is it calculated?**

* **Definition:** Return on Investment (ROI) measures the profit generated relative to the cost of a marketing campaign.

* **Formula (Method 1):**

  $$
  ROI = \frac{(Sales\ Growth - Marketing\ Cost)}{Marketing\ Cost}
  $$

  **Example:** Sales growth = $200,000, Marketing cost = $55,000 →

  $$
  ROI = \frac{200,000 - 55,000}{55,000} = 2.6
  $$

  * ROI > 1 = profitable; ROI = 1 = break-even.

* **Formula (Method 2 using LTV):**
  ROI can also be measured by monitoring **Customer Lifetime Value (LTV)** trends over time.
  An **increasing LTV** indicates improved ROI.

---

### **2. What is ROAS and how is it calculated?**

* **Definition:** Return on Ad Spend (ROAS) measures the revenue earned for every dollar spent on advertising.

* **Formula:**

  $$
  ROAS = \frac{Revenue}{Ad\ Spend}
  $$

* **Example:**

  * A goal of 5:1 ROAS means $5 revenue per $1 spent.
  * Per-channel goals could be **3:1 for search ads** and **4:1 for display ads**.

---

### **3. What is LTV and how is it used in ROI measurement?**

* **Definition:** Customer Lifetime Value (LTV) is the **average revenue per customer** over a period.

* **Formula (Method 1):**

  $$
  LTV = \frac{Total\ Revenue}{Number\ of\ Customers}
  $$

* **Formula (Method 2):**

  $$
  LTV = Average\ Order\ Value \times Purchase\ Frequency
  $$

* **Key ratio (LTV:CAC):**

  $$
  LTV:CAC\ Ratio = \frac{LTV}{CAC}
  $$

---

### **4. What is CAC and how is it calculated?**

* **Definition:** Customer Acquisition Cost (CAC) is the average cost of acquiring one paying customer.

* **Formula:**

  $$
  CAC = \frac{Total\ Marketing\ +\ Sales\ Costs}{Number\ of\ New\ Customers\ Acquired}
  $$

---

### **5. What is Lifetime ROAS and how is it measured?**

* **Definition:** Combines ROAS with LTV to measure long-term ad performance.

* **Formula:**

  $$
  Lifetime\ ROAS = \frac{Number\ of\ New\ Customers \times Total\ LTV}{Ad\ Spend}
  $$

---

### **6. What are the different testing methods in digital marketing?**

* **A/B Testing (Split/Bucket Test):**

  * Compares **two variants** with one differing element.
  * Users are randomly split **50/50** between A & B.
  * Metrics tested: conversion rate, CTR, bounce rate, etc.
  * Example: Testing **headline A vs headline B** in Google Ads.

* **Redirect Testing:**

  * Compares **two separate pages/URLs** (e.g., two different landing pages).
  * Useful for **complete redesigns**.

* **Multivariate Testing:**

  * Tests multiple elements (e.g., CTA + image + headline) simultaneously.
  * Identifies not only best individual variants but also **best combinations**.

---

### **7. What statistical terms are important in A/B testing?**

* **Statistical significance:** Determines if results are due to real differences or random chance.
* **Confidence level:** Likelihood results would hold true if test ran longer (95% is standard).
* **Confidence interval:** Range of possible values, accounting for margin of error.
* **Margin of error:** Difference between sample test results and theoretical true results.

---

### **8. What are micro-conversions and macro-conversions?**

* **Micro-conversion:** Small steps toward purchase (e.g., email signup, chatbot interaction).

* **Macro-conversion:** Final purchase or completed transaction.

* **Example from case study:**

  * **Email sign-ups** ↑ 21% (micro) but **purchases stayed flat** (macro).
  * **Chatbot** hit both micro and macro targets.
  * **Blog visits** missed both.

---

### **9. Can you give a case study example of using A/B testing and analytics?**

**Good Boy Studios (PetStar App):**

* **Challenge:** Users dropped off at Event 6 (placing mouth markers) and Event 8 (recording video).
* **Solution:**

  * A/B tests in Firebase with user tips:

    * Variant A (“pinch to zoom”) → +44% completion.
    * Variant B (“mouth closed”) → +25% completion.
  * Added a **RECORDING SONG indicator** → boosted recording completion from **62% to 67%** (70% for iOS).
* **Result:** Higher completion rates, more conversions to premium service.

---

### **10. How do you plan an A/B test?**

* **Steps:**

  1. Define problem/goal.
  2. Form a hypothesis (problem, change, expected result).
  3. Create variants (A = control, B = one change).
  4. Decide on metrics (primary + secondary).
  5. Set success definition (e.g., +15% CTR).
  6. Choose sample size, duration, confidence level.
  7. Run, measure, and analyze results.

---

# **Project Title:** **Suggest a New Product Category Based on Internal Site Search Data**

# **Project Scenario**

A fine art supplies e-commerce store observed growing interest in broader **craft supplies**. To validate where to expand first, we analyzed **internal site search terms** and categorized them into **Yarn**, **Candle making**, **Jewelry making**, or **Other** to identify which category had the most demand.

# **Project Objective**

Use internal search analytics to:

* Categorize queries into actionable product categories
* Quantify demand by **unique searches** per category
* Recommend the **top category** for near-term product expansion

# Project Description (Step by Step)

1. **Collect data**
   Exported a list of internal search terms with **Unique Searches** for the last period.

2. **Define categories**
   Dropdown options: **Yarn**, **Jewelry making**, **Candle making**, **Other**.

3. **Classify terms**
   Assigned each search term to one category (e.g., “velvet yarn” → Yarn; “soy candle wax” → Candle making; “earring making supplies” → Jewelry making).

4. **Build a pivot table**

   * Rows: **Category**
   * Values: **SUM of Unique Searches**
   * Filtered out **(blank)** to remove the spurious “0” row.
  
**Snippet URL (visual):**
[https://github.com/aminbiography/Google-Digital-Marketing---E-commerce-Professional-Certificate/blob/main/bar-graph-chart-image/Suggest%20a%20new%20product%20category%20based%20on%20search%20data.jpg](https://github.com/aminbiography/Google-Digital-Marketing---E-commerce-Professional-Certificate/blob/main/bar-graph-chart-image/Suggest%20a%20new%20product%20category%20based%20on%20search%20data.jpg)

5. **Compute totals** (from the finished pivot)

   * **Yarn:** 81,114
   * **Candle making:** 57,872
   * **Jewelry making:** 47,595
   * **Other:** 21,753

6. **Interpret results**
   **Yarn** received the highest volume of unique searches, indicating strongest on-site demand and discovery interest.

7. **Recommend actions**

   * Prioritize **Yarn** assortment expansion (weights, fibers, colors)
   * Optimize navigation & search synonyms (e.g., “dk yarn”, “super bulky”, “sock wool”)
   * Feature yarn bundles/learn-to-knit kits; cross-sell needles, patterns, storage
   * Test content & SEO for high-volume modifiers (“chunky yarn”, “knitting kits”)
   * Monitor post-launch metrics: product views, add-to-carts, product conversion rate, and return rate

**Live Project Source (Spreadsheet):**
[https://docs.google.com/spreadsheets/d/1xsX9zzfGzcH_O5vkRURxbP3Eu9SO1CsTHekLbtBiZ94/edit?usp=drive_link](https://docs.google.com/spreadsheets/d/1xsX9zzfGzcH_O5vkRURxbP3Eu9SO1CsTHekLbtBiZ94/edit?usp=drive_link)

# Project Conclusion

Internal site search clearly indicates **Yarn** as the leading opportunity. By expanding yarn SKUs and improving findability, the store can capture demonstrated demand quickly. Continued tracking via product views, add-to-carts, and product conversion rate will validate impact and guide iterative optimization.

## **Project Credit**  
- **Project Executed & Presented By**: *Mohammad Aminul Islam* (Digital Marketing & E-commerce Analyst)  
- **Data Source:** Internal site search logs & pivot analysis in Google Sheets
- **Project Source**: Google Digital Marketing & E-commerce hands-on project (Coursera)  
- **Guidance & Framework**: Google Digital Marketing & E-commerce documentation & instructions  
- **Copyright**: © 2022 Google LLC. Google and the Google logo are trademarks of Google LLC. Other names may be trademarks of their respective companies.  

---

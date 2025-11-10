# 🧾 GroMart Online Delivery Impact Analysis (2016 Case Study)

##  Project Overview
This project analyzes **GroMart’s 2016 partnership with SwiftCart**, where select California ZIP codes received online delivery service.  
The goal was to assess how the **introduction of online ordering** impacted **offline (in-store) sales**, and whether the program boosted total revenue or cannibalized existing store performance.  
It also explores **which income and growth segments (A–D quadrants)** benefited most from the rollout.

---

##  Key Questions
1. How was the **online rollout** implemented across ZIP codes?  
2. What was the **overall impact** on in-store sales after January 2016?  
3. Did the online delivery program **affect offline store performance** within those ZIP codes?  
4. Which customer segments (A–D quadrants) showed the **highest and lowest growth**?  
5. How can GroMart leverage these insights to plan future expansions?

---

##  Methodology
- **Dataset:** Monthly in-store sales for all ZIP codes across **2015–2016**, combined with ZIP-level demographics (Median Income, Population, Pharmacy presence).  
- **Cleaning:** Corrected online-availability flags for pre-2016 months to reflect true rollout timing.  
- **Metrics:**  
  - % Change in sales = *(2016 − 2015) / 2015 × 100*  
  - Income and growth splits based on median thresholds.  
- **Segmentation:** ZIP codes divided into **four quadrants**:
  - **Median Income (High / Low)**
  - **Sales Growth (High / Low)**

---

##  Rollout Overview
- **Before 2016:** All stores operated exclusively offline.  
- **January 2016:** SwiftCart delivery launched across ~30 ZIP codes in a single-phase rollout.  
- **Pattern:** Rapid adoption in Q1 2016, stabilizing by mid-year.  
- **Adoption trend:** Initially led by high-income ZIPs, followed by gradual expansion into lower-income areas.  
- **Observation:** A controlled pilot approach that allowed clear before-and-after comparisons.

---

##  Before vs After Impact

| Period | Segment | Avg In-Store Sales | Trend |
|:-------|:---------|------------------:|:------|
| **2015 (Before)** | All ZIPs | Baseline performance | Stable sales across stores |
| **2016 (After)** | Online ZIPs | ↑ ~2–3 % | Slight lift, no cannibalization |
|  | Offline ZIPs | ≈ Flat | Unaffected by rollout |

➡ **Takeaway:** Online delivery **complemented** in-store performance rather than replacing it.  
In ZIPs with online service, in-store sales stayed stable or rose slightly — indicating **synergistic growth across channels**.

---

##  Quadrant Classification

Each ZIP code was categorized into one of four **income–growth quadrants**, revealing distinct customer and market behaviors.

### **Quadrant A – High Income & High Growth**
- Represents **affluent ZIP codes** with strong adoption of online delivery.  
- Stores retained solid offline sales while benefiting from digital expansion.  
- Indicates **sustained consumer loyalty and channel coexistence**.

### **Quadrant B – High Income & Low Growth**
- Consists of **wealthy areas** showing smaller or negative growth.  
- Potential **market saturation** or channel substitution, where online ordering replaced some in-store visits.  
- Suggests the need for **targeted retention strategies**.

### **Quadrant C – Low Income & High Growth**
- Reflects **value-driven customers** who quickly embraced online convenience.  
- Despite lower income levels, these ZIPs showed **significant percentage growth**.  
- Highlights a **strong opportunity segment** for expansion and loyalty programs.

### **Quadrant D – Low Income & Low Growth**
- Represents **price-sensitive ZIPs** with minimal change in overall sales.  
- Possibly constrained by lower digital access or delivery awareness.  
- Requires **localized marketing and education efforts** to stimulate demand.

---

##  Key Insights
- **Rollout success:** Online delivery expanded access without disrupting existing store operations.  
- **No offline cannibalization:** In-store sales remained steady or improved slightly post-rollout.  
- **Complementary channels:** Online and offline performance moved together — overall revenue increased.  
- **Growth segments (A & C):** Both affluent and value markets responded positively.  
- **Underperforming segments (B & D):** Need better pricing, awareness, and engagement tactics.

---

##  Overall Findings (2016 vs 2015 Medians)

| Quadrant | Median Income ($) | Median % Change | Key Behavior |
|-----------|-----------------:|----------------:|---------------|
| **A – High Income & High Growth** | 44 304 | +2.77 % | Strong growth in affluent ZIPs. |
| **B – High Income & Low Growth** | 44 833 | −4.01 % | Slight decline — market saturation. |
| **C – Low Income & High Growth** | 30 927 | +2.52 % | High adoption among value markets. |
| **D – Low Income & Low Growth** | 30 137 | −2.06 % | Minimal change — needs awareness. |

---

##  Final Summary
> “GroMart’s 2016 online delivery rollout with SwiftCart drove incremental growth while maintaining strong offline sales.  
> The program achieved inclusive adoption across both high- and low-income ZIPs, proving that digital expansion complemented rather than cannibalized traditional retail.”  

---

##  Tools Used
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Google Colab / Jupyter Notebook** for EDA and visualization  
- **PowerPoint** for executive presentation  
- **GitHub** for project documentation and version control  



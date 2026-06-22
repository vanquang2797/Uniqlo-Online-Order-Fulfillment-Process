# 🛍️ Uniqlo – Online Order Fulfillment Process (BPM)

> Business Process Management analysis of Uniqlo's online sales and order fulfillment process — including BPMN modeling (As-Is / To-Be), VA–BVA–NVA classification, and quantitative CTE performance evaluation.

---

## 📌 Project Overview

| Item | Detail |
|------|--------|
| **Course** | Business Process Management – ITS713 (Banking University of HCMC) |
| **Methodology** | BPM lifecycle: Process Discovery → Modeling → Analysis → Redesign → Evaluation |
| **Tool** | BPMN 2.0 |

---

## 🗂️ Repository Structure

```
uniqlo-bpm/
├── README.md
├── BPMN_AsIs_Uniqlo.png              # As-Is process diagram with CT/PT annotations
├── BPMN_ToBe_Uniqlo.png              # To-Be redesigned process diagram
├── BPM_Report_Uniqlo.pdf             # Full report (Vietnamese)
└── docs/
    └── VA_BVA_NVA_Analysis.xlsx      # Task classification table (20 tasks)
```

---

## 🔍 Project Summary

This project analyzes the **online order fulfillment process** of Uniqlo Vietnam — from the moment a customer accesses the platform to successful delivery or return handling.

The study covers:
- Process architecture identification and core process decomposition
- BPMN 2.0 modeling of the current (As-Is) process
- VA / BVA / NVA task classification across 20 tasks
- Process redesign (To-Be) applying 6 redesign heuristics
- Quantitative cycle time analysis and CTE comparison

---

## 📊 Quantitative Results

### As-Is vs. To-Be Comparison

| Metric | As-Is | To-Be | Change |
|--------|-------|-------|--------|
| Total tasks | 20 | 17 | −3 tasks |
| Total Cycle Time (CT) | 2,257.4 min (~37.6 hrs) | 1,850.8 min (~30.8 hrs) | **−406.6 min (~6.8 hrs)** |
| Total Processing Time (PT) | 570.1 min | 548.5 min | −21.6 min |
| **CTE (Cycle Time Efficiency)** | **25.25%** | **29.63%** | **+4.38%** |

### Bottleneck Analysis (As-Is)
- **Staff lane:** 630 min CT vs. 30 min PT — manual inventory check caused 8+ hrs of idle time
- **Delivery lane:** 1,562 min CT vs. 512 min PT — reactive failure handling caused repeated re-delivery loops

---

## 🔧 Redesign Heuristics Applied

| Heuristic | Change Made |
|-----------|-------------|
| **Task elimination** | Removed redundant "Prepare goods" step (merged into packaging) |
| **Task combination** | Merged order recording + payment processing into one seamless flow |
| **Resequencing** | Moved inventory check to immediately after "Add to cart" (before checkout) |
| **Standardization** | Set 24-hour confirmation rule; auto-cancel if no customer response |
| **Resource optimization** | System auto-notifies customer before delivery; reduces manual follow-up |
| **Automation** | Real-time inventory sync, auto order confirmation after payment, auto-cancellation |

---

## ⚙️ Tools & Methods

| Category | Tool / Method |
|----------|---------------|
| Process modeling | BPMN 2.0 |
| Analysis framework | VA / BVA / NVA classification |
| Performance metric | Cycle Time Efficiency (CTE = PT / CT × 100%) |
| Documentation | Microsoft Word |
| References | Dumas et al. (2018) – *Fundamentals of Business Process Management* |

---

## 💡 Key Skills Demonstrated

`BPMN 2.0 Modeling` · `As-Is / To-Be Process Design` · `VA–BVA–NVA Analysis`  
`Cycle Time Efficiency (CTE)` · `Process Redesign Heuristics` · `Bottleneck Identification`  
`Quantitative Process Evaluation` · `Business Process Management`

---

## 📎 Related Projects

| Project | Description |
|---------|-------------|
| [Highlands Coffee – BA](../highlands-coffee-ba) | BABOK v3 BRD with 120+ requirements |
| [Smart CRM System – PMBOK](../smart-crm-pmbok) | PM with PMBOK 5th Ed., WBS, RACI matrix |
| [COOPSHOP Functional Testing](../coopshop-testing) | 29 test cases, bug reporting |
| [Supply Chain Database Design](../supply-chain-database) | 18-table SQL Server schema, ERD, CDM |

---

## 👤 Author

**Võ Văn Quang**  
MIS Student – Banking University of Ho Chi Minh City  
📧 [LinkedIn Profile](https://www.linkedin.com/in/vo-van-quang/)

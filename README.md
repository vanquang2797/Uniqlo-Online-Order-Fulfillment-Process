Uniqlo – Online Order Fulfillment Process (BPM)


Business Process Management analysis of Uniqlo's online sales and order fulfillment process — including BPMN modeling (As-Is / To-Be), VA–BVA–NVA classification, and quantitative CTE performance evaluation.




📌 Project Overview

ItemDetailCourseBusiness Process Management – ITS713 (Banking University of HCMC)TeamThịt Kho Trứng (5 members)RoleTeam member – VA/BVA/NVA analysis & quantitative evaluationMethodologyBPM lifecycle: Process Discovery → Modeling → Analysis → Redesign → EvaluationToolBPMN 2.0


🗂️ Repository Structure

uniqlo-bpm/
├── README.md
├── BPMN_AsIs_Uniqlo.png              # As-Is process diagram with CT/PT annotations
├── BPMN_ToBe_Uniqlo.png              # To-Be redesigned process diagram
├── BPM_Report_Uniqlo.pdf             # Full report (Vietnamese)
└── docs/
    └── VA_BVA_NVA_Analysis.xlsx      # Task classification table (20 tasks)


🔍 Project Summary

This project analyzes the online order fulfillment process of Uniqlo Vietnam — from the moment a customer accesses the platform to successful delivery or return handling.

The study covers:


Process architecture identification and core process decomposition
BPMN 2.0 modeling of the current (As-Is) process
VA / BVA / NVA task classification across 20 tasks
Process redesign (To-Be) applying 6 redesign heuristics
Quantitative cycle time analysis and CTE comparison



📊 Quantitative Results

As-Is vs. To-Be Comparison

MetricAs-IsTo-BeChangeTotal tasks2017−3 tasksTotal Cycle Time (CT)2,257.4 min (~37.6 hrs)1,850.8 min (~30.8 hrs)−406.6 min (~6.8 hrs)Total Processing Time (PT)570.1 min548.5 min−21.6 minCTE (Cycle Time Efficiency)25.25%29.63%+4.38%

Bottleneck Analysis (As-Is)


Staff lane: 630 min CT vs. 30 min PT — manual inventory check caused 8+ hrs of idle time
Delivery lane: 1,562 min CT vs. 512 min PT — reactive failure handling caused repeated re-delivery loops



🔧 Redesign Heuristics Applied

HeuristicChange MadeTask eliminationRemoved redundant "Prepare goods" step (merged into packaging)Task combinationMerged order recording + payment processing into one seamless flowResequencingMoved inventory check to immediately after "Add to cart" (before checkout)StandardizationSet 24-hour confirmation rule; auto-cancel if no customer responseResource optimizationSystem auto-notifies customer before delivery; reduces manual follow-upAutomationReal-time inventory sync, auto order confirmation after payment, auto-cancellation


⚙️ Tools & Methods

CategoryTool / MethodProcess modelingBPMN 2.0Analysis frameworkVA / BVA / NVA classificationPerformance metricCycle Time Efficiency (CTE = PT / CT × 100%)DocumentationMicrosoft WordReferencesDumas et al. (2018) – Fundamentals of Business Process Management


💡 Key Skills Demonstrated

BPMN 2.0 Modeling · As-Is / To-Be Process Design · VA–BVA–NVA Analysis

Cycle Time Efficiency (CTE) · Process Redesign Heuristics · Bottleneck Identification

Quantitative Process Evaluation · Business Process Management



👤 Author

Võ Văn Quang

MIS Student – Banking University of Ho Chi Minh City

📧 LinkedIn Profile (https://www.linkedin.com/in/vo-van-quang/)

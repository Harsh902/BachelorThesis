# 📄 Paper Analysis Notes (Guided by 3 Questions)

---

## 1. Basic Info
- **Citation:**  
- **Year / Venue:**  
- **Type:** (Survey / Primary)  
- **Variant focus (TSP / VRP / VRPTW / other):**  

---

## 2. Approaches Suggested (Q1)
- **Which ML/AI approaches for discrete/combinatorial optimization are discussed or proposed?**  
  - [ ] Supervised learning  
  - [ ] Reinforcement learning  
  - [ ] Graph neural networks  
  - [ ] Evolutionary / metaheuristic hybrids  
  - [ ] Other (specify):  
- **Brief description of the method(s):**  
- **Taxonomy position (if survey):**  

---

## 3. Promising Approaches (Q2)
- **Which approaches does the paper itself highlight as promising?**  
- **Evidence (results, benchmarks, comparisons):**  
- **Strengths:**  
- **Limitations / open challenges:**  
- **Do other surveys or primary sources agree? (cross-check):**  

---

## 4. Usability for VRPTW (Q3)
- **Does the approach apply directly to VRPTW?** (Yes / No)  
- **If not, can it be adapted? How?**  
- **What constraints would need modification (time windows, capacity, multi-vehicle, etc.)?**  
- **Potential obstacles (e.g., scalability, generalization):**  
- **My assessment of fit for VRPTW:** (High / Medium / Low)  

---

## 5. Critical Takeaways
- **What does this paper add to my understanding of AI+combinatorial optimization?**  
- **Which open problems or future directions are most relevant for VRPTW?**  
- **Other references from this paper I should follow up on:**  

---

---

# 📊 Comparison Table Across Papers (Condensed View)

| Paper (Citation) | Year | Type | Approaches Suggested (Q1) | Promising? (Q2) | VRPTW Usability (Q3) | Notes |
|------------------|------|------|---------------------------|-----------------|-----------------------|-------|
| Example: Wu et al. | 2024 | Survey | NCO: RL, GNN, hybrids | RL + GNN flagged as promising | Medium – needs extension for time windows | Good taxonomy, covers SOTA |
| Example: Bogyrbayeva et al. | 2024 | Survey | ML + classical hybrids | Hybrids seen as practical | High – adaptable to VRPTW constraints | Systematic overview, well-cited |
| Example: Liu et al. | 2023 | Survey | Heuristics, metaheuristics | Strong for VRPTW but less “AI” | Already used in VRPTW | Background only, not cutting-edge |
| Example: Smith et al. | 2019 | Primary | Deep RL for TSP | Promising for small TSPs | Low – scalability issues | Baseline to compare DL methods |

# 🧮 AI & TSP/VRP Paper Sorting / Classification Template

---

## Paper: [Citation / Title]

---

### Q1: Which ML/AI approaches for usage in discrete/combinatorial optimization have been suggested?

- **List of approaches seen in this paper:**  
  - e.g. Supervised learning (e.g. pointer networks)  
  - Graph neural networks  
  - Reinforcement learning  
  - Deep learning / Transformer-based  
  - Hybrid ML + heuristic/metaheuristic  
  - Large Language Model (LLM) hybrids  
  - Other (specify):  

- **Taxonomy / classification (if survey):**  
  - How does the paper group the approaches?  
  - What are the axes of classification (e.g., construction vs improvement, exact vs approximate, offline vs online)  

---

### Q2: Which of these approaches appear promising?

- **Criteria for “promising”:**  
  - High solution quality (close to optimum)  
  - Good scalability (can handle large instance sizes)  
  - Good generalization (beyond training / synthetic instances)  
  - Efficient inference / compute time  
  - Adaptability to variant constraints (time windows, capacity, multiple vehicles etc.)  

- **Which approaches meet many of these criteria (according to this paper)?**  
  - List them, with brief evidence (e.g. “GNN + heuristic hybrid achieves small optimality gap on 10,000 nodes”; “Transformer model fast inference but weaker on constraint handling”)  

- **Which approaches have major drawbacks / limitations (in this paper)?**  
  - e.g. weak generalization, high memory, poor handling of constraints, high training cost etc.  

---

### Q3: Which of the remaining ones (or the promising ones) are usable or adaptable for **our VRPTW** variant?

- **Does the approach already handle these constraint(s)?**  
  - Time windows (TW): yes / no  
  - Multiple vehicles / capacity constraints / depot constraints etc.: yes / no  

- **If not, can it be adapted?**  
  - What modifications would be needed? (e.g. add time window penalty, modify architecture, change input representation)  
  - What are likely obstacles (e.g. training data, computational cost)  

- **Estimated fit:** High / Medium / Low — with reasons  

---

### Critical Summary Notes

- **Key takeaways:** What this paper taught me about AI + combinatorial optimization, especially regarding VRPTW  
- **Open problems / future directions mentioned:**  
- **Other references to check (from this paper):**

---

---

## Comparison Across Papers (so far)

| Paper | Approaches (Q1) | Most Promising (Q2) | VRPTW Usability (Q3) | Fit (High/Med/Low) | Notes / Trade-offs |
|--------|------------------|-----------------------|-------------------------|----------------------|----------------------|
| [Citation 1] | e.g. GNN, RL, Hybrid | Hybrid + GNN | Needs TW handling; capacity ok | Medium | Good on scalability; less on constraints |
| [Citation 2] | Supervised pointer nets etc. | Fast inference, medium quality | No TW, single vehicle only | Low | Could serve as baseline / component |
| … | … | … | … | … | … |

---


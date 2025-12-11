#  Visual Storytelling with [DanielStorytelling]

---

##  Innovation Summary

**I modified the sequence predictor to increased number of layers for expectations seeing the more accurate outcome for the text , images generations(dual generation)**

---

## 📊 Key Results

| Metric | Baseline | Improved | Change |
| :--- | :--- | :--- | :--- |
| BLEU-1 | 0.44 | 0.55 | **+22.2%** ||

---

##  Most Important Finding

> The innovation reduced repetitive phrases by **35%** (BLEU IMPROVED = +22.2%) in long sequences, as shown in **[this visual visualization](results/comparative_analysis/repetition_analysis.png)**.

---

##  How to Reproduce

1.  `pip install -r requirements.txt`
2.  Open `experiments.ipynb`
3.  Run cells sequentially (takes ~2 hours on GPU)

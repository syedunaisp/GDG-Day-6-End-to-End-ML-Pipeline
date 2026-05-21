# 🎓 Day 6 — End-to-End ML Pipeline Workshop

**AI/ML Build Week | Student Marks Prediction System**

---

## 🗂️ Files

| File | Purpose |
|------|---------|
| `data.csv` | Synthetic student dataset (~300 rows) |
| `without_pipeline.ipynb` | Manual ML workflow — no pipelines |
| `test_without_pipeline.ipynb` | Inference without pipeline (feels painful) |
| `with_pipeline.ipynb` | Clean ML workflow using sklearn Pipelines |
| `test_with_pipeline.ipynb` | Inference with pipeline (dramatically simpler) |

---

## 🧠 Teaching Flow

```
without_pipeline.ipynb   →   test_without_pipeline.ipynb
       ↓ (students feel the pain)
with_pipeline.ipynb      →   test_with_pipeline.ipynb
       ↓ (students see the contrast)
        "Pipelines make sense now."
```

---

## ⚙️ Setup

```bash
pip install pandas numpy scikit-learn joblib
```

**Recommended Workshop Flow:**

1. `without_pipeline.ipynb` — build & train manually
2. `test_without_pipeline.ipynb` — **discuss pain points with the class**
3. `with_pipeline.ipynb` — introduce pipelines as the solution
4. `test_with_pipeline.ipynb` — show how clean inference becomes

---

## 🎯 Task

**Regression** — Predict `final_score` (0–100) from:
- `study_hours`, `attendance_percentage`, `sleep_hours`, `previous_exam_score`
- `internet_access`, `parental_education`, `extracurricular_activity`, `part_time_job`, `motivation_level`

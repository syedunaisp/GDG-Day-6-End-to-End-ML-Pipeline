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

---

## ⚙️ Setup

```bash
pip install pandas numpy scikit-learn joblib
```


## 🎯 Task

**Regression** — Predict `final_score` (0–100) from:
- `study_hours`, `attendance_percentage`, `sleep_hours`, `previous_exam_score`
- `internet_access`, `parental_education`, `extracurricular_activity`, `part_time_job`, `motivation_level`

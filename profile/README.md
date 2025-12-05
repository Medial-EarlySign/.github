# Production-Ready ML Infrastructure for EMR

**Medial EarlySign's Machine Learning infrastructure and development toolkit for building, validating, and deploying predictive clinical models using Electronic Medical Records (EMR).**

This award-winning framework used in production across multiple sites and recognized in the [CMS AI Health Outcomes Challenge](https://www.cms.gov/priorities/innovation/innovation-models/artificial-intelligence-health-outcomes-challenge) offers an end-to-end solution for high-stakes medical AI.

The repository provides the:

* [Wiki](https://medial-earlysign.github.io/MR_Wiki): a complete knowledge base for our proprietary and open sourced ML infrastructure and workflows.
* [medpython](https://github.com/Medial-EarlySign/medpython): The infrastructure library to train, test, deploy our models
* [MR_Tools](https://github.com/Medial-EarlySign/MR_Tools): Utilities that uses MR_LIBS library and were used directly to develop our products


---

## ✨ Complete ML Pipeline Components

Our system is designed to handle the unique challenges of clinical data, providing robust tools for every phase of model development:

| Phase | Component & Focus | Key Capabilities |
| :--- | :--- | :--- |
| **Ingestion** | `RepProcessors` (Data Preparation) | Cleans, aggregates, and standardizes raw EMR signals into meaningful, temporal records. |
| **Modeling** | `FeatureGenerators` & `MedAlgo` | Transforms data into complex features (e.g., embeddings) and handles training, calibration, and feature importance analysis (e.g., XGBoost, MedPredictor). |
| **Deployment Prep** | `PostProcessors` | Essential steps for production readiness: score calibration, explainability analysis, and **fairness adjustment**. |
| **Validation** | `Medial Tools` (Evaluation) | Utilities like **`AutoTest`** and `bootstrap_analysis` ensure model quality, robustness, and performance over time. |

---

## 🔗 Documentation Links

Start your exploration by reviewing the high-level **[Wikimedial Overview]** and the **[Installation Guide]** for setting up the environment and the Python API.

| Section | Description | Link |
| :--- | :--- | :--- |
| **Wikimedial Overview** | The essential starting point for all users. | [View Overview](https://medial-earlysign.github.io/MR_Wiki/index.html) |
| **Tuttorials** | The essential starting point for all users. | [View Overview](https://medial-earlysign.github.io/MR_Wiki/Tutorials) |
| **Installation** | Environment setup (Python API & C++ Library). | [View Installation](https://medial-earlysign.github.io/MR_Wiki/Installation/index.html) |

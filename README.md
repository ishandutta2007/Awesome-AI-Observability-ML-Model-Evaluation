# Awesome-AI-Observability-ML-Model-Evaluation

# Top AI Observability & ML Model Evaluation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on ML & LLM Production Monitoring, Data & Concept Drift Detection, Model Evaluation Suites, OpenTelemetry AI Tracing & Data Quality Observability*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Observability & ML Model Evaluation**. These tools monitor machine learning and generative AI models in production, detect data/concept drift and performance degradation, evaluate LLM/RAG faithfulness and hallucination rates, and validate training and inference data pipelines.

**Examples** include Arize AI, Fiddler AI, WhyLabs, TruEra (Snowflake), Galileo, Arthur AI, Gantry, Monte Carlo Data, Evidently Cloud, Weights & Biases, and evidentlyai/evidently (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for ML/LLM drift and evaluation suites (`Evidently`, `Arize Phoenix`, `DeepChecks`, `NannyML`, `WhyLogs`), OpenTelemetry AI observability (`OpenLIT`, `OpenLLMetry`, `Langfuse`), unit-test LLM eval frameworks (`DeepEval`, `Ragas`, `Promptfoo`, `Giskard`), and data validation engines (`Great Expectations`, `Soda Core`) — ideal for MLOps engineers, data scientists, and AI platform teams building transparent, self-hosted observability stacks.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Arize AI (Arize AX)](https://arize.com)**  
  Enterprise ML and LLM observability platform offering root-cause drift analysis, embedding visualization, OpenTelemetry span tracing, and automated AI evaluation workflows.

- **[Fiddler AI](https://fiddler.ai)**  
  Enterprise AI observability and governance platform providing real-time predictive ML drift monitoring, explainability (SHAP), hallucination metrics, and sub-100ms guardrails.

- **[Evidently Cloud](https://evidentlyai.com)**  
  Managed cloud platform built around Evidently for tracking ML and LLM evaluation test suites, data drift dashboards, synthetic test generation, and regression alerts.

- **[Weights & Biases (Models & Weave)](https://wandb.ai)**  
  End-to-end AI developer platform uniting ML experiment tracking, model registry governance, and W&B Weave for LLM/agent tracing and evaluation.

- **[Snowflake AI Observability (formerly TruEra)](https://snowflake.com)**  
  Enterprise AI quality and observability suite providing automated RAG groundedness scoring, model diagnostics, explainability, and governance inside cloud data platforms.

- **[Galileo](https://rungalileo.io)**  
  Enterprise AI evaluation and observability suite featuring real-time hallucination guardrails, agentic trajectory metrics, RAG attribution scoring, and automated error clustering.

- **[Arthur AI (Arthur Scope & Shield)](https://arthur.ai)**  
  Enterprise model monitoring and real-time LLM firewall platform delivering performance tracking, fairness/bias auditing, data drift alerts, and prompt protection.

- **[WhyLabs](https://whylabs.ai)**  
  Privacy-first AI observability and security platform powered by statistical data profiling (`whylogs`) to detect data drift, anomalies, and LLM policy violations without raw data ingestion.

- **[Monte Carlo Data](https://montecarlodata.com)**  
  End-to-end data and AI observability platform monitoring data pipelines, feature stores, and vector ingestion workflows for freshness, volume, and schema anomalies.

- **[Gantry / Braintrust / LangSmith](https://braintrust.dev)**  
  Continuous AI evaluation and production feedback platforms designed to turn production model logs into curated golden datasets and prevent quality regressions across releases.


## Open-Source GitHub Projects

- **[Evidently (`evidentlyai/evidently`)](https://github.com)**  
  Flagship open-source (`Apache-2.0`) Python library and monitoring UI for evaluating, testing, and monitoring ML and LLM models—featuring 100+ built-in metrics for data drift, classification/regression quality, and LLM-as-a-judge checks.

- **[Arize Phoenix (`Arize-ai/phoenix`)](https://github.com)**  
  Open-source (`ELv2`) OpenTelemetry-native AI observability and evaluation tool featuring interactive trace waterfalls, embedding drift clusters, RAG diagnostics, and notebook integration.

- **[Deepchecks (`deepchecks/deepchecks`)](https://github.com)**  
  Comprehensive open-source (`AGPL-3.0`) continuous validation suite for tabular, NLP, and computer-vision ML models covering data integrity, train-test drift, and model performance checks.

- **[NannyML (`NannyML/nannyml`)](https://github.com)**  
  Open-source (`Apache-2.0`) post-deployment ML monitoring library capable of estimating model performance (`CBPE` / `DLE`) in production even when ground-truth labels are delayed or unavailable.

- **[whylogs (`whylabs/whylogs`)](https://github.com)**  
  Lightweight open-source (`Apache-2.0`) data and ML logging standard generating mergeable statistical profiles to track data drift, data quality constraints, and LLM telemetry at scale.

- **[Langfuse (`langfuse/langfuse`)](https://github.com)**  
  Leading self-hostable open-source LLM engineering platform for full-stack trace observability, dataset evaluation runs, prompt versioning, and cost/latency analytics.

- **[OpenLIT (`openlit/openlit`)](https://github.com)**  
  Open-source (`Apache-2.0`) OpenTelemetry-native AI engineering platform providing zero-code instrumentation for 50+ LLM providers, vector databases, GPU metrics, and hallucination evaluations.

- **[OpenLLMetry (`traceloop/openllmetry`)](https://github.com)**  
  Open-source (`Apache-2.0`) set of OpenTelemetry instrumentation extensions capturing standardized traces and metrics from LLMs and agent frameworks into any OTel backend.

- **[TruLens (`truera/trulens`)](https://github.com)**  
  Open-source (`MIT`) library for systematically evaluating and tracking LLM and RAG applications using programmable Feedback Functions (Groundedness, Context Relevance, Answer Relevance).

- **[DeepEval (`confident-ai/deepeval`)](https://github.com)**  
  Popular open-source (`Apache-2.0`) Pytest-style LLM evaluation framework offering 40+ research-backed metrics for faithfulness, hallucination, tool correctness, and CI/CD regression testing.

- **[Ragas (`explodinggradients/ragas`)](https://github.com)**  
  Widely adopted open-source (`Apache-2.0`) evaluation and synthetic test-data generation toolkit specialized in measuring retrieval precision, recall, and faithfulness in RAG pipelines.

- **[Giskard (`Giskard-AI/giskard-oss`)](https://github.com)**  
  Open-source (`Apache-2.0`) automated QA and testing framework for both traditional ML models and LLM agents scanning for performance bias, spurious correlations, hallucinations, and prompt injections.

- **[Opik (`comet-ml/opik`)](https://github.com)**  
  Open-source (`Apache-2.0`) end-to-end LLM evaluation and tracing platform from Comet built for logging high-volume traces, curating datasets, and running automated evaluations.

- **[Alibi Detect (`SeldonIO/alibi-detect`)](https://github.com)**  
  Open-source (`Apache-2.0`) Python library from Seldon focused on outlier, adversarial, and drift detection across tabular, text, image, and time-series ML workloads.

- **[MLflow (`mlflow/mlflow`)](https://github.com)**  
  Industry-standard open-source (`Apache-2.0`) MLOps platform featuring experiment tracking, model registry, `mlflow.evaluate()` automated ML/LLM scoring, and OpenTelemetry tracing.

- **[Great Expectations (`great-expectations/great_expectations`)](https://github.com)**  
  Leading open-source (`Apache-2.0`) data quality and pipeline observability framework preventing upstream schema shifts and corrupted features from silently degrading ML models.

- **[Promptfoo (`promptfoo/promptfoo`)](https://github.com)**  
  Fast open-source (`MIT`) CLI and library for declarative model/prompt benchmarking, CI/CD regression gating, and automated red-teaming.

### Additional Strong Open-Source Options

- **[River (`online-ml/river`)](https://github.com)** and **[scikit-multiflow](https://github.com)** for streaming online machine learning and real-time concept-drift detectors (`ADWIN`, `DDM`, `Page-Hinkley`).
- **[Fairlearn (`fairlearn/fairlearn`)](https://github.com)** and **[AI Fairness 360 (`Trusted-AI/AIF360`)](https://github.com)** for auditing and mitigating demographic bias and fairness metrics in predictive ML models.
- **[SHAP (`shap/shap`)](https://github.com)** and **[LIME (`marcotcr/lime`)](https://github.com)** for model-agnostic feature attribution and local explainability alongside drift diagnostics.
- **[Soda Core (`sodadata/soda-core`)](https://github.com)** and **[Elementary (`elementary-data/elementary`)](https://github.com)** for open-source data observability, anomaly detection, and dbt pipeline monitoring.
- **[Prometheus + Grafana + SigNoz (`SigNoz/signoz`)](https://github.com)** for self-hosted OpenTelemetry backends storing and alerting on ML/LLM latency, drift, and evaluation metrics.

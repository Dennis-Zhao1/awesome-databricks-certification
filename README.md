# Awesome Databricks Certification [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md) [![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

> Curated resources for every Databricks certification exam — study guides, hands-on labs, courses, practice questions, and books for Data Engineer, Data Analyst, Spark Developer, Machine Learning, and Generative AI exams.

## Contents

- [General Resources](#general-resources)
- [Courses & Learning](#courses--learning)
- [Databricks Certified Data Engineer Associate](#databricks-certified-data-engineer-associate)
- [Databricks Certified Data Engineer Professional](#databricks-certified-data-engineer-professional)
- [Databricks Certified Data Analyst Associate](#databricks-certified-data-analyst-associate)
- [Databricks Certified Apache Spark Developer Associate](#databricks-certified-apache-spark-developer-associate)
- [Databricks Certified Machine Learning Associate](#databricks-certified-machine-learning-associate)
- [Databricks Certified Machine Learning Professional](#databricks-certified-machine-learning-professional)
- [Databricks Certified Generative AI Engineer Associate](#databricks-certified-generative-ai-engineer-associate)
- [Communities](#communities)
- [Contributing](#contributing)

---

## General Resources

### Official

- [Databricks Certification Overview](https://www.databricks.com/learn/certification) - Official certification portal with exam registration, pricing, and requirements.
- [Databricks Academy](https://www.databricks.com/learn/training) - Free on-demand courses and learning paths from Databricks.
- [Databricks Documentation](https://docs.databricks.com/) - Official product documentation covering all platform features tested across certifications.
- [Delta Lake Documentation](https://docs.databricks.com/en/delta/index.html) - Official Delta Lake guide — core topic tested across all Data Engineer and Analyst exams.
- [Unity Catalog Documentation](https://docs.databricks.com/en/data-governance/unity-catalog/index.html) - Official Unity Catalog guide for data governance, tested across multiple certifications.

### Exam Overview

All exams: $200 USD, multiple choice, proctored online. Databricks does not publish official passing scores (community-reported ~70%). [Full catalog](https://www.databricks.com/learn/certification).

| Exam | Level | Questions | Time |
| ---- | ----- | --------- | ---- |
| [Data Engineer Associate](https://www.databricks.com/learn/certification/data-engineer-associate) | Associate | 45 | 90 min |
| [Data Engineer Professional](https://www.databricks.com/learn/certification/data-engineer-professional) | Professional | 59 | 120 min |
| [Data Analyst Associate](https://www.databricks.com/learn/certification/data-analyst-associate) | Associate | 45 | 90 min |
| [Apache Spark Developer Associate](https://www.databricks.com/learn/certification/apache-spark-developer-associate) | Associate | 45 | 120 min |
| [Machine Learning Associate](https://www.databricks.com/learn/certification/machine-learning-associate) | Associate | 48 | 90 min |
| [Machine Learning Professional](https://www.databricks.com/learn/certification/machine-learning-professional) | Professional | 59 | 120 min |
| [Generative AI Engineer Associate](https://www.databricks.com/learn/certification/genai-engineer-associate) | Associate | 45 | 90 min |

Free accreditations (for customers/partners): Databricks Fundamentals, Generative AI Fundamentals, AI Agent Fundamentals, Platform Administrator, Cloud Platform Architect.

### Cross-Certification Study Guides

- [kengio/databricks-certification-study-guide](https://github.com/kengio/databricks-certification-study-guide) - Obsidian-based study guide covering Databricks certifications with Anki cards, labs, and learning paths. Aligned to 2025-2026 exam guides.
- [kasztp/dbx-exam-guide](https://github.com/kasztp/dbx-exam-guide) - No-BS exam prep guide for Databricks Data Engineer certifications with infographics.

### Practice Question Banks

| Platform | Free | DE Assoc | DE Prof | Analyst | Spark Dev | ML Assoc | ML Prof | GenAI |
| -------- | ---- | -------- | ------- | ------- | --------- | -------- | ------- | ----- |
| [Databricks Academy](https://customer-academy.databricks.com/learn) | Customers | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| [CertPrepNow](https://certprepnow.com/) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| [OpenExamPrep](https://open-exam-prep.com/practice/exams/technology/databricks) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| [BricksNotes](https://bricksnotes.com/practice) | ✓ | ✓ | | | | | | |
| [Udemy Practice Tests](https://www.udemy.com/courses/search/?q=databricks+certification+practice) | Paid | ✓ | ✓ | | | | | |

---

## Courses & Learning

### Official (Free)

- [Databricks Academy](https://customer-academy.databricks.com/learn) - Free self-paced courses for all certification paths. Instructor-led available (~$1,000-$1,500).
- [Free Certification Overview Courses](https://www.databricks.com/blog/getting-databricks-certified-now-easier-free-overview-courses) - Free overview course for each certification exam.

### Microsoft Learn (Free)

- [Data Analytics Solution with Azure Databricks](https://learn.microsoft.com/en-us/training/paths/data-engineer-azure-databricks/) - Data ingestion, Azure Data Lake, Azure SQL. 6 modules, intermediate level.
- [Data Engineering Solution Using Azure Databricks](https://learn.microsoft.com/en-us/training/courses/dp-750t00) - Data orchestration and security (course DP-750).
- [Build ML Solutions Using Azure Databricks](https://learn.microsoft.com/en-us/training/paths/build-operate-machine-learning-solutions-azure-databricks/) - ML at scale. 8 modules.

### Udemy

- [Azure Databricks & Spark For Data Engineers](https://www.udemy.com/course/azure-databricks-spark-core-for-data-engineers/) - By Ramesh Retnasamy. 4.6★, 160K students. 20h, updated 2026.
- [Databricks Certified DE Associate - Preparation](https://www.udemy.com/course/databricks-certified-data-engineer-associate/) - By Derar Alhussein. 4.5★, 107K students. 5h, updated 2026.
- [PySpark - Apache Spark Programming for Beginners](https://www.udemy.com/course/apache-spark-programming-in-python-for-beginners/) - By Prashant Kumar Pandey. 4.6★, 97K students. 28h, updated 2026.
- [Databricks Certified DE Professional - Preparation](https://www.udemy.com/course/databricks-certified-data-engineer-professional/) - By Derar Alhussein. 4.6★, 32K students. 5h, updated 2026.
- [Azure Databricks and Spark SQL (Python)](https://www.udemy.com/course/azure-databricks-and-spark-sql-python/) - By Malvik Vaghadia. 4.7★, 29K students. 17h, updated 2026.
- [Azure Databricks E2E: Unity Catalog, DABs, CI/CD](https://www.udemy.com/course/azure-databricks-end-to-end-project-with-unity-catalog-cicd/) - By Shanmukh Sattiraju. 4.6★, 16K students. 21h, updated 2026.
- [Databricks Certified DE Associate - Bootcamp](https://www.udemy.com/course/databricks-certified-data-engineer-associate-bootcamp/) - By Ansh Lamba. 4.6★, 10K students. 19h, updated 2026.

### Coursera

- [Enterprise AI and Data Engineering with Databricks](https://www.coursera.org/specializations/enterprise-ai-data-engineering-databricks) - 5-course specialization by Pragmatic AI Labs.
- [Mastering Azure Databricks for Data Engineers](https://www.coursera.org/specializations/packt-mastering-azure-databricks-for-data-engineers) - 3-course series by Packt. 6,500+ enrolled.

### Free Community Courses

- [Databricks DE Associate Certification Course](https://www.youtube.com/watch?v=0Hd5vYqin7w) - Free 7.5-hour course on freeCodeCamp by Andrew Brown. 145K+ views.

---

## Databricks Certified Data Engineer Associate

> [Official Exam Page](https://www.databricks.com/learn/certification/data-engineer-associate) · 45 questions · 90 min · $200

### Books

- [derar-alhussein/oreilly-databricks-dea](https://github.com/derar-alhussein/oreilly-databricks-dea) - Code exercises from *Databricks Certified Data Engineer Associate Study Guide* (O'Reilly, by Derar Alhussein).

### Courses

- [derar-alhussein/Databricks-Certified-Data-Engineer-Associate](https://github.com/derar-alhussein/Databricks-Certified-Data-Engineer-Associate) - Udemy course companion repo with labs covering all 5 DE Associate exam sections.
- [timothywarner-org/databricks](https://github.com/timothywarner-org/databricks) - Crash course resource list by Tim Warner with slides, labs, and practice exams.

### Study Notes

- [shantanukhond/Databricks-Data-Engineer-Associate-Notes](https://github.com/shantanukhond/Databricks-Data-Engineer-Associate-Notes) - Comprehensive notes covering architecture, Delta Lake, transformations, UDFs, and SQL.
- [mo-nirvana/Databricks.DataEngineer.Prep](https://github.com/mo-nirvana/Databricks.DataEngineer.Prep) - Personal experience and study plan with course recommendations.
- [wang-yuhao/databricks-de-associate-prep](https://github.com/wang-yuhao/databricks-de-associate-prep) - 7-day intensive study plan for the DE Associate exam.

### Hands-On Labs

- [jrlasak/databricks_data_engineer_associate_cert_prep](https://github.com/jrlasak/databricks_data_engineer_associate_cert_prep) - End-to-end lab covering Auto Loader, Medallion Architecture, SCD Type 2, Unity Catalog, and Jobs.
- [jrlasak/databricks_apparel_streaming](https://github.com/jrlasak/databricks_apparel_streaming) - DLT apparel streaming pipeline lab with medallion architecture and synthetic data.
- [jrlasak/databricks_pyspark_cert_zenith](https://github.com/jrlasak/databricks_pyspark_cert_zenith) - E-commerce analytics pipeline lab for PySpark cert prep with DataFrame API and Streaming.
- [RESGAD-TECH-UK/Databricks-Data-Engineer-Certification-Guide](https://github.com/RESGAD-TECH-UK/Databricks-Data-Engineer-Certification-Guide) - Comprehensive guide with topic breakdowns, study tips, and practice strategies.
- [Galius5136/databricks-spark-3.5-cert-prep](https://github.com/Galius5136/databricks-spark-3.5-cert-prep) - Agent-skill study system for Spark 3.5 certification with sources linked to official docs.

### Practice Exams

- [BricksNotes DE Associate Practice Exam](https://bricksnotes.com/practice) - Community-built free mock exam with explanations. No paywall.
- [Udemy DE Associate Practice Tests](https://www.udemy.com/course/practice-exams-databricks-certified-data-engineer-associate/) - Timed mock exams with 55 questions each, matching real exam format.

---

## Databricks Certified Data Engineer Professional

> [Official Exam Page](https://www.databricks.com/learn/certification/data-engineer-professional) · 59 questions · 120 min · $200

### Courses

- [derar-alhussein/Databricks-Certified-Data-Engineer-Professional](https://github.com/derar-alhussein/Databricks-Certified-Data-Engineer-Professional) - Udemy course companion repo with labs for DE Professional certification.

### Study Resources

- [AG8999/Databricks-Data-Engineer-professional-exam](https://github.com/AG8999/Databricks-Data-Engineer-professional-exam) - Exam prep materials for the Data Engineer Professional certification.
- [RESGAD-TECH-UK/Databricks-Data-Engineer-Certification-Guide](https://github.com/RESGAD-TECH-UK/Databricks-Data-Engineer-Certification-Guide) - Covers both Associate and Professional with topic breakdowns, study tips, and practice strategies.
- [Databricks Lakeflow Documentation](https://docs.databricks.com/en/delta-live-tables/index.html) - Official guide to Lakeflow Declarative Pipelines (formerly DLT), a major Professional exam topic.
- [Databricks Asset Bundles Documentation](https://docs.databricks.com/en/dev-tools/bundles/index.html) - Official guide to DABs for CI/CD and deployment, tested on the Professional exam.
- [Databricks Workflows Documentation](https://docs.databricks.com/en/workflows/index.html) - Official guide to job orchestration, scheduling, and multi-task workflows.

### Practice Exams

- [OpenExamPrep DE Professional Tests](https://open-exam-prep.com/practice/exams/technology/databricks) - Free practice questions with instant scoring and explanations.
- [Udemy DE Professional Practice Tests](https://www.udemy.com/course/practice-exams-databricks-certified-data-engineer-professional/) - Timed mock exams matching real exam format.

---

## Databricks Certified Data Analyst Associate

> [Official Exam Page](https://www.databricks.com/learn/certification/data-analyst-associate) · 45 questions · 90 min · $200

### Books

- [PacktPublishing/Databricks-Certified-Data-Analyst-Associate-Exam-Prep](https://github.com/PacktPublishing/Databricks-Certified-Data-Analyst-Associate-Exam-Prep) - Packt companion repo with Databricks SQL files and datasets.

### Study Resources

- [vicsz/databricks-analyst-study-notes](https://github.com/vicsz/databricks-analyst-study-notes) - Comprehensive study notes with exam insights, based on the Mar 2025 exam guide.
- [Databricks SQL Documentation](https://docs.databricks.com/en/sql/index.html) - Official SQL reference covering SQL Editor, warehouses, and query optimization tested on the exam.
- [Databricks AI/BI Dashboards Documentation](https://docs.databricks.com/en/dashboards/index.html) - Official guide to dashboards and visualizations, a key exam topic.

### Practice Exams

- [CertPrepNow Data Analyst Practice](https://certprepnow.com/databricks-data-analyst) - Free practice questions for SQL analytics, dashboards, and AI/BI Genie topics.
- [OpenExamPrep Data Analyst Tests](https://open-exam-prep.com/practice/exams/technology/databricks) - Free practice questions with instant scoring and explanations.

---

## Databricks Certified Apache Spark Developer Associate

> [Official Exam Page](https://www.databricks.com/learn/certification/apache-spark-developer-associate) · 45 questions · 120 min · $200

### Books

- [Learning Spark, 2nd Edition (O'Reilly)](https://www.oreilly.com/library/view/learning-spark-2nd/9781492050032/) - Comprehensive book by Damji et al. covering Spark 3.x fundamentals tested on the exam.

### Study Resources

- [Realsid/databricks-spark-certification](https://github.com/Realsid/databricks-spark-certification) - Guide for Databricks Spark certification with study notes and exam topics.
- [Apache Spark Documentation](https://spark.apache.org/docs/latest/) - Official Spark docs covering DataFrame API, Spark SQL, and Structured Streaming.
- [Databricks Spark Guide](https://docs.databricks.com/en/spark/index.html) - Databricks-specific Spark documentation covering cluster management and Delta Lake integration.
- [Spark By Examples](https://sparkbyexamples.com/) - Community tutorials with PySpark and Scala code examples for DataFrame operations, SQL, and Streaming.

### Practice Exams

- [CertPrepNow Spark Developer Practice](https://certprepnow.com/databricks-spark-developer) - Free practice questions with explanations for DataFrame API, Spark SQL, and Streaming topics.
- [OpenExamPrep Spark Developer Tests](https://open-exam-prep.com/practice/exams/technology/databricks) - Free practice questions with instant scoring and explanations.

---

## Databricks Certified Machine Learning Associate

> [Official Exam Page](https://www.databricks.com/learn/certification/machine-learning-associate) · 48 questions · 90 min · $200

### Study Notes

- [Zillin/databricks-machine-learning-associate-exam-guide](https://github.com/Zillin/databricks-machine-learning-associate-exam-guide) - Cheat sheet, comparison tables, and exam outline (Mar 2025 version).
- [redashu/Databricks_Machine_learning_Associates_2026](https://github.com/redashu/Databricks_Machine_learning_Associates_2026) - Study resources with Academy learning plan and Udemy recommendations.

### Hands-On Labs

- [devesshhh/databricks-ml-certification](https://github.com/devesshhh/databricks-ml-certification) - Notebooks covering PySpark, MLflow, AutoML, Model Deployment, and MLOps. Author passed July 2025.
- [tharhtetsan/Databricks-Certified-Machine-Learning-Associate-and-Professional](https://github.com/tharhtetsan/Databricks-Certified-Machine-Learning-Associate-and-Professional) - Jupyter notebooks covering both ML Associate and Professional exam objectives.

### Study Resources

- [MLflow Documentation](https://mlflow.org/docs/latest/index.html) - Official MLflow docs covering experiment tracking, model registry, and deployment.
- [Databricks AutoML Documentation](https://docs.databricks.com/en/machine-learning/automl/index.html) - Official AutoML guide for automated model training and hyperparameter tuning.

### Practice Exams

- [OpenExamPrep ML Associate Tests](https://open-exam-prep.com/practice/exams/technology/databricks) - Free practice questions with instant scoring and explanations.
- [CertPrepNow ML Associate Practice](https://certprepnow.com/databricks-ml-associate) - Free practice questions on data preparation, model development, deployment, and MLOps.

---

## Databricks Certified Machine Learning Professional

> [Official Exam Page](https://www.databricks.com/learn/certification/machine-learning-professional) · 59 questions · 120 min · $200

### Study Resources

- [alex-fedorenk0/db-ml-prof-exam](https://github.com/alex-fedorenk0/db-ml-prof-exam) - Detailed 4-section prep notes covering experimentation, lifecycle, deployment, and monitoring.
- [tharhtetsan/Databricks-Certified-Machine-Learning-Associate-and-Professional](https://github.com/tharhtetsan/Databricks-Certified-Machine-Learning-Associate-and-Professional) - Jupyter notebooks covering both ML Associate and Professional exam objectives.
- [MLflow Documentation](https://mlflow.org/docs/latest/index.html) - Official MLflow docs covering experiment tracking, model registry, and deployment tested on the exam.
- [Databricks Model Serving Documentation](https://docs.databricks.com/en/machine-learning/model-serving/index.html) - Official guide to model endpoints, A/B testing, and monitoring.
- [Databricks Feature Engineering Documentation](https://docs.databricks.com/en/machine-learning/feature-store/index.html) - Official guide to Feature Store and feature engineering workflows.

### Practice Exams

- [CertPrepNow ML Professional Practice](https://certprepnow.com/databricks-ml-professional) - Free practice questions on experimentation, model lifecycle, deployment, and monitoring.
- [OpenExamPrep ML Professional Tests](https://open-exam-prep.com/practice/exams/technology/databricks) - Free practice questions with instant scoring and explanations.

---

## Databricks Certified Generative AI Engineer Associate

> [Official Exam Page](https://www.databricks.com/learn/certification/genai-engineer-associate) · 45 questions · 90 min · $200

### Books

- [rkaushik2007/Databricks-Certified-Generative-AI-Engineer-Associate-Study-Guide](https://github.com/rkaushik2007/Databricks-Certified-Generative-AI-Engineer-Associate-Study-Guide) - O'Reilly companion repo with labs for *GenAI Engineer Associate Study Guide* by Rajaniesh Kaushikk.
- [snowleafbooks/databricks-genai](https://github.com/snowleafbooks/databricks-genai) - Companion repo for Snowleaf Press *GenAI Engineer Associate Exam Prep* with runnable notebooks (2026).
- [monika-4dec/Databricks-Generative-AI-Associate-Certification](https://github.com/monika-4dec/Databricks-Generative-AI-Associate-Certification) - O'Reilly companion repo for *GenAI Engineer Associate Study Guide* by Dr. Monika Arora.

### Study Notes

- [vicsz/databricks-genai-cert](https://github.com/vicsz/databricks-genai-cert) - Detailed study notes with prompt design rules, task-model mapping, and RAG strategies.

### Hands-On Labs

- [codingdoneraitt/Databricks-Certified-Generative-AI-Engineer-Associate](https://github.com/codingdoneraitt/Databricks-Certified-Generative-AI-Engineer-Associate) - 37 labs across 8 modules covering every exam objective (March 2026 version).
- [btriani/databricks-genai-lab-guide](https://github.com/btriani/databricks-genai-lab-guide) - 10 labs with Jupyter notebooks, architecture diagrams, cost estimates, and exam tips.
- [keshabmanni/DatabricksGenAIAssociate_CertExamPrep](https://github.com/keshabmanni/DatabricksGenAIAssociate_CertExamPrep) - Interactive web study guide with progress tracking and practice quizzes.

### Study Resources

- [Databricks Vector Search Documentation](https://docs.databricks.com/en/generative-ai/vector-search.html) - Official guide to vector search for RAG applications.
- [Mosaic AI Agent Framework Documentation](https://docs.databricks.com/en/generative-ai/agent-framework/index.html) - Official guide to building and deploying AI agents on Databricks.

### Practice Exams

- [OpenExamPrep GenAI Engineer Tests](https://open-exam-prep.com/practice/exams/technology/databricks) - Free practice questions with instant scoring and explanations.
- [CertPrepNow GenAI Engineer Practice](https://certprepnow.com/databricks-genai-engineer) - Free practice questions on RAG, AI agents, model evaluation, and deployment.

---

## Communities

- [Databricks Community Forum](https://community.databricks.com/) - Official forum for Data Engineering, ML, SQL, and certification discussions.
- [r/databricks](https://www.reddit.com/r/databricks/) - ~20K members. General discussion, troubleshooting, and certification tips.
- [Stack Overflow [databricks]](https://stackoverflow.com/questions/tagged/databricks) - Technical Q&A for PySpark, Delta Lake, cluster config, and SQL.
- [DataTalks.Club Slack](https://datatalks.club/slack) - 80K+ members. DE, ML, MLOps courses, and career advice.
- [Databricks Discord](https://discord.me/databricks) - Real-time troubleshooting, networking, and certification discussions.
- [Databricks User Groups](https://usergroups.databricks.com/) - Regional and interest-based chapters worldwide.
- [Data+AI Summit](https://www.databricks.com/dataaisummit) - Annual Databricks conference with 800+ sessions covering all certification topics.
- [Data Engineer Handbook](https://github.com/DataExpert-io/data-engineer-handbook) - 40K+ star curated DE resource collection. Covers Spark, Delta Lake, and more.

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related rights to this work.

Independent educational resource. Not affiliated with or endorsed by Databricks, Inc.

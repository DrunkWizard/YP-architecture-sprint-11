| Категория | Статус | Технологии и методологии | Комментарий |
| :--- | :--- | :--- | :--- |
| **Техники и методологии** | ВНЕДРЯТЬ (ADOPT) | Data Mesh, CI/CD, Infrastructure as Code (IaC), MLOps | Data Mesh как подход к децентрализации данных по доменам. CI/CD и IaC для автоматизации и надёжности. |
| | ЗАМОРОЗИТЬ (HOLD) | Монолитная разработка в DWH, ручное развёртывание | Отказываемся от старых подходов, которые замедляют time-to-market. |
| **Платформы и инфраструктура** | ВНЕДРЯТЬ (ADOPT) | AWS (S3, Glue, EKS), Snowflake, Apache Kafka, Kubernetes | Основа нашей новой облачной платформы. Snowflake для DWH, Kafka для потоков, S3 для Data Lake. |
| | ВЫВОДИТЬ (RETIRE) | MS SQL Server 2008, физические серверы под DWH | Устаревшая и непроизводительная СУБД, от которой мы уходим. |
| **Языки и фреймворки** | ВНЕДРЯТЬ (ADOPT) | Python (для Spark и ML), Go / Java (для сервисов), SQL | Python становится основным языком для работы с данными. Go/Java уже используются в финтехе. |
| | ВЫВОДИТЬ (RETIRE) | Power Builder | Устаревший язык для легаси-интерфейса. |
| **Инструменты** | ВНЕДРЯТЬ (ADOPT) | Apache Spark/Flink, Apache Airflow, Metabase/Superset, DataHub/Amundsen, Great Expectations, Prometheus/Grafana, Kubeflow | Полный набор инструментов для оркестрации (Airflow), обработки (Spark), BI (Metabase), каталогизации (DataHub) и качества данных (Great Expectations). |
| | ВЫВОДИТЬ (RETIRE) | Power BI (на старом DWH), Apache Camel | Power BI заменяется на Metabase/Superset, а старая шина Apache Camel — на современную связку Kafka + API Gateway. |
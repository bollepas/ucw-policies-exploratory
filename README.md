# ucw-policies-exploratory
## Exploratory Analysis

### Project Description
Exploratory Analysis of the UCW Substance Use Policy Implementation

### Project Title
Exploring UCW’s Policy Effectiveness and Compliance

### Objective
To identify trends and insights within UCW’s Substance Use Policy by exploring its structure, coverage, and compliance mechanisms.

### Dataset
The dataset includes:
- Segmented policy sections (e.g., responsibilities, definitions, and scope)
- References to associated policies and procedures
- Applicable legislation impacting the policy

### Methodology
#### 1. Data Ingestion
- Segmented data from the policy document was ingested into AWS S3 (`policy-trf-ucw`) for exploratory analysis.

#### 2. Data Profiling
- AWS Glue DataBrew profiled the dataset to identify:
  - Coverage of policy sections
  - Frequency of legislative references
  - Key focus areas (e.g., safety-sensitive operations)

#### 3. Data Transformation
- AWS Glue ETL pipelines were used to:
  - Aggregate definitions and responsibilities for trend analysis.
  - Analyze legislative references for compliance patterns.
  - Prepare data for visualization.

#### 4. Data Visualization
- Insights were visualized using Tableau to:
  - Highlight relationships between responsibilities and legislative requirements.
  - Identify gaps in coverage or ambiguous areas.

### Tools and Technologies
- **AWS Services:** S3, Glue DataBrew, and Glue ETL for profiling and transformation.
- **Data Visualization:** Tableau for creating insights dashboards.

### Deliverables
- Exploratory insights into UCW’s policy structure and compliance measures.
- Interactive dashboards showcasing key trends and relationships.
- A report summarizing exploratory findings with recommendations.

### Conclusion
Exploratory analysis provided actionable insights into UCW’s Substance Use Policy, highlighting areas for improvement and reinforcing compliance measures. AWS services ensured efficient data handling, while visualizations enhanced stakeholder understanding of the policy’s impact.

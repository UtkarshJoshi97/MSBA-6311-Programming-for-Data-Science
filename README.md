# MSBA-6311-Programming-for-Data-Science

# Introduction

Objective

This open project challenges students to address a real-world problem with business value using niche libraries or advanced technologies. Students must identify gaps in existing solutions and propose approaches to mitigate or resolve the issue.

Target Audience

The presentation is aimed at a diverse jury with varied professional backgrounds, emphasizing clarity, innovation, and practical application.

# Trends Marketplace: Optimizing Data Analysis with Optuna and Python

# Hypothesis
Our project investigates the hypothesis:

"Optuna optimizes hyperparameters for predictive modeling on customer segmentation data, improving classification accuracy while reducing computational overhead."

# Approach
## Step 1: Define Business Value

Identify the Problem:

We focused on optimizing predictive modeling performance by leveraging Optuna for hyperparameter tuning. This approach addresses the common gap in real-world analytics: manual and inefficient parameter tuning, which often leads to suboptimal results.

Impact on Businesses:

Efficient hyperparameter optimization enhances model accuracy, reduces computation costs, and accelerates decision-making processes—critical for industries relying on data-driven insights.

Example: Retail businesses optimizing inventory forecasting models or financial institutions fine-tuning risk prediction algorithms.

## Step 2: Data Analysis

Data Extraction:

Data was retrieved directly from an SQL database to simulate real-world data pipeline scenarios, where most data resides in data warehouses. This ensures our approach remains practical and industry-relevant.

Technology Application:

The dataset was analyzed using default model hyperparameters as a baseline. Optuna was then applied to perform hyperparameter optimization, providing a comparative framework.

Challenges Documented:

Handling large-scale data during extraction and pre-processing.

Integration of SQL-based data pipelines with Python analysis workflows.

Fine-tuning Optuna trials to achieve a balance between computational efficiency and optimal results.

## Step 3: Solution Development

Baseline vs. Optimized Parameters:

Default hyperparameters were evaluated first, serving as a performance benchmark.

Using Optuna, we implemented trial-based optimization to identify the best hyperparameters.

Comparison metrics (e.g., accuracy, RMSE, runtime) demonstrated the significant improvement achieved through Optuna’s optimization process.

Gap Mitigation:

Real-World Applicability: The SQL integration ensures the solution is directly applicable to real-world scenarios where data is stored in warehouses.

Efficiency: Optuna’s automated search reduced manual effort and improved model performance, addressing the inefficiencies of traditional tuning.

Advantages:

Scalability: Easily extended to different datasets and machine learning models.

Flexibility: Supports integration with various frameworks like Scikit-learn, TensorFlow, and PyTorch.

Limitations:

Initial setup requires understanding of Optuna’s API and trial management.
Computationally intensive for large-scale datasets or complex models.

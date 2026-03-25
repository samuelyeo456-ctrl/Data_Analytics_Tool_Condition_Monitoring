# Data_Analytics_Tool_Condition_Monitoring
This project predicts CNC tool wear using regression. It compares CA, RFE, and PCA selection over two cutters , finding polynomial regression with RFE most effective for modeling non-linear patterns.

In the use of milling machines, the wear of an insert tool is a crucial factor in achieving straight
and sharp cuts. Using a tool that experiences significant wear will result in rough edges, which is
undesirable. The flank wear of each individual tool can be determined using a microscope and a
digital camera. However, given the number of tools used, this process is not feasible as it is very
time-consuming. Therefore, assessing the wear of a tool is the focus of this project. Data on the
tool’s cutting force and its wear are measured. To derive more useful information from this data,
feature extraction is also performed. Using this data, this project aims to develop a reliable and
robust model to predict the wear of a tool.

Predictive accuracy, robustness of Polynomial and Multiple Linear Regression models across two distinct cutter datasets are evaluated. By implementing feature selection techniques like RFE, PCA, and Correlation Analysis, I identified that Recursive Feature Elimination (RFE) provided the best predictive power by capturing non-linear relationships. While Polynomial Regression delivered superior accuracy, testing against a second "real-world" dataset revealed a performance drop (lower R²), highlighting the critical importance of model generalization and the challenges of machine variability in manufacturing environments.

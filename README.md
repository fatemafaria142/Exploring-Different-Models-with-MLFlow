
# MLflow

MLflow is an open source platform for managing the end-to-end machine learning lifecycle.

## Components:

1. **Tracking:** Allows you to track experiments to record and compare parameters and results.
2. **Models:** Manage and deploy models from various ML libraries to different serving platforms.
3. **Projects:** Package ML code in a reusable, reproducible form for sharing and production.
4. **Model Registry:** Centralize model storage, versioning, and transitions across lifecycle stages.
5. **Model Serving:** Host MLflow models as REST endpoints for easy deployment and query.

# MLflow Logging Functions

| Function         | Description                                  |
|------------------|----------------------------------------------|
| `log_param`      | Log a single parameter for experiment tracking.                    |
| `log_params`     | Log multiple parameters for experiment tracking.                   |
| `log_metric`     | Log a single metric for experiment tracking.                       |
| `log_metrics`    | Log multiple metrics for experiment tracking.                      |
| `log_artifact`   | Log a single artifact file for experiment tracking.                 |
| `log_artifacts`  | Log multiple artifact files for experiment tracking.               |
| `log_dict`       | Log a dictionary of key-value pairs for experiment tracking.        |
| `log_text`       | Log a text string for experiment tracking.                          |
| `log_figure`     | Log a matplotlib figure for experiment tracking.                    |
| `log_image`      | Log an image file for experiment tracking.                          |





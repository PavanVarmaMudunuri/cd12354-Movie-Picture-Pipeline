# Project Deployment & Pipeline Evidence

This folder contains the verification screenshots and logs for the **Movie Picture Pipeline** CI/CD project:

1. **[all_workflows.png](all_workflows.png)**: Overview of all GitHub Actions workflow runs.
2. **[frontend_ci_success.png](frontend_ci_success.png)**: Frontend Continuous Integration pipeline passing (Linting, Testing, and Docker build).
3. **[backend_ci_success.png](backend_ci_success.png)**: Backend Continuous Integration pipeline passing (Flake8 linting, Pytest testing, and Docker build).
4. **[frontend_cd_success.png](frontend_cd_success.png)**: Frontend Continuous Deployment pipeline passing (ECR push, Kustomize edit, and EKS rollout).
5. **[backend_cd_success.png](backend_cd_success.png)**: Backend Continuous Deployment pipeline passing (ECR push, Kustomize edit, and EKS rollout).
6. **[terraform_init.png](terraform_init.png)**: Terraform initialization in workspace.
7. **[terraform_apply_output.png](terraform_apply_output.png)**: Terraform apply output showing created ECR repositories, EKS cluster, and IAM user.
8. **[frontend_app_running.png](frontend_app_running.png)**: Working frontend UI running at `localhost:3000` displaying the movie catalog from the backend API.
9. **[backend_api_running.png](backend_api_running.png)**: Working backend Flask API running and returning movie catalog in JSON format (target port 5000).

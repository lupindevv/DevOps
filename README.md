# Hello Azure VM CI/CD

Simple static website used for testing GitHub Actions CI/CD deployment to Azure VMs.

## Planned flow

- Push to `dev` → deploy to Dev VM
- PR from `dev` to `main` → approval required
- Merge to `main` → deploy to Main VM
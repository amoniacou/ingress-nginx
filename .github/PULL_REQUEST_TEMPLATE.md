<!--- Provide a general summary of your changes in the Title above --->

## 📝 Description / Why we need it
<!--- What is the purpose of this change? (e.g., Fixing sync workflow, updating actions, modifying GHCR paths) -->


## ⚙️ Type of change
<!--- Put an `x` in the boxes that apply: -->
- [ ] CI/CD infrastructure change (modifying workflows, scripts, or permissions)
- [ ] Dependabot dependency update
- [ ] Documentation or README update
- [ ] Other (please specify)


## 🛠️ How has this been tested?
<!--- Since we no longer run automated E2E test workflows, please describe how you verified this change -->
- [ ] Tested manually via `workflow_dispatch` (manual trigger) on a test branch
- [ ] Validated workflow syntax against GitHub schema
- [ ] No testing required (e.g., typo fix, documentation)


## 📋 Checklist:
<!--- Put an `x` in all the boxes that apply. -->
- [ ] My changes follow the new automated sync flow (no upstream code modifications).
- [ ] The workflow changes (if any) do not break the sync with `kubernetes/ingress-nginx`.
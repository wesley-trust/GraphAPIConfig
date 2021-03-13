# GraphAPIConfig
Configuration files for deployment with the GraphAPI
## Azure AD
### Conditional Access
|  Main  | Develop |
| :----: | :-----: |
|[![Build Status](https://dev.azure.com/wesleytrust/GraphAPI/_apis/build/status/SVC-CA%3BENV-P%3B%20Conditional%20Access?branchName=main)](https://dev.azure.com/wesleytrust/GraphAPI/_build/latest?definitionId=2&branchName=main)|[![Build Status](https://dev.azure.com/wesleytrust/GraphAPI/_apis/build/status/SVC-CA%3BENV-D%3B%20Conditional%20Access?branchName=develop)](https://dev.azure.com/wesleytrust/GraphAPI/_build/latest?definitionId=5&branchName=develop)|

JSON Definitions of:
- Conditional Access Policies
- Conditional Access Locations
- Groups
#### CI/CD Pipeline
- Validating the input
- Evaluation the input to create a plan for approval
- Deploying to an environment, applying the plan
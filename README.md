# GraphAPIConfig
Configuration files for deployment with the GraphAPI and Pipeline definitions
## Azure AD
| Service |  Main  | Develop |
|:---| :----: | :-----: |
| Conditional Access Policies |[![Build Status](https://dev.azure.com/wesleytrust/GraphAPI/_apis/build/status/Azure%20AD/Conditional%20Access/SVC-CA%3BENV-P%3B%20Policies?branchName=main)](https://dev.azure.com/wesleytrust/GraphAPI/_build/latest?definitionId=2&branchName=main)|[![Build Status](https://dev.azure.com/wesleytrust/GraphAPI/_apis/build/status/Azure%20AD/Conditional%20Access/SVC-CA%3BENV-D%3B%20Policies?branchName=develop)](https://dev.azure.com/wesleytrust/GraphAPI/_build/latest?definitionId=5&branchName=develop)|
| Groups |[![Build Status](https://dev.azure.com/wesleytrust/GraphAPI/_apis/build/status/Azure%20AD/Groups/SVC-AD%3BENV-P%3B%20Groups?branchName=main)](https://dev.azure.com/wesleytrust/GraphAPI/_build/latest?definitionId=9&branchName=main)|[![Build Status](https://dev.azure.com/wesleytrust/GraphAPI/_apis/build/status/Azure%20AD/Groups/SVC-AD%3BENV-D%3B%20Groups?branchName=develop)](https://dev.azure.com/wesleytrust/GraphAPI/_build/latest?definitionId=7&branchName=develop)|
| Named Locations |[![Build Status](https://dev.azure.com/wesleytrust/GraphAPI/_apis/build/status/Azure%20AD/Named%20Locations/SVC-AD%3BENV-P%3B%20Named%20Locations?branchName=main)](https://dev.azure.com/wesleytrust/GraphAPI/_build/latest?definitionId=10&branchName=main)|[![Build Status](https://dev.azure.com/wesleytrust/GraphAPI/_apis/build/status/Azure%20AD/Named%20Locations/SVC-AD%3BENV-D%3B%20Named%20Locations?branchName=develop)](https://dev.azure.com/wesleytrust/GraphAPI/_build/latest?definitionId=11&branchName=develop)|
| Licensing |  |  |
## Endpoint Manager (Intune)
| Service |  Main  | Develop |
|:---| :----: | :-----: |
| Device Compliance Policy: Windows 10 |  |
| Device Configuration Policy: Windows 10 |  |
### JSON Definitions of:
- Conditional Access Policies
- Groups
- Named Locations
### CI/CD Pipeline to Import, Plan and Deploy:
- Validating the input against set criteria
- Evaluating the input against what is deployed, to create a change plan for approval
- Deploying to a specified environment, applying the approved plan
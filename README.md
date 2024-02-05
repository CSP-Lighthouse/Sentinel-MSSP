# CSP Lighthouse MDR One-Click deploy for Microsoft Sentinel



![CSP_LH_HORIZONTAL-07](https://github.com/CSP-Lighthouse/Sentinel-MSSP/assets/117652672/06c83f13-1d79-441f-afce-85cdcfea6e46)

[CSP's](https://csp.global/) one click to deploy Microsoft Sentinel into your environment. Simply click the button below and follow the instructions.

## CSP MDR - Deployment Options

A few deployments are available through Microsoft Sentinel!

| Items | Deploy | 
| :---| :---| 
| [Microsoft Sentinel](https://github.com/mastersoho/CSPLighthouse/tree/main/microsoft-sentinel) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmastersoho%2FCSPLighthouse%2Fmain%2Fmicrosoft-sentinel%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2Fmastersoho%2FCSPLighthouse%2Fmain%2Fmicrosoft-sentinel%2Fuidefinition.json) |
| [Azure Lighthouse](https://github.com/mastersoho/CSPLighthouse/tree/main/deploy-lighthouse) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmastersoho%2FCSPLighthouse%2Fmain%2Fdeploy-lighthouse%2Flighthousedeploy.json) |

| Group Name  | Role Id                        | Name | Description |
| ------------------- | ------------------------------ | -----|------------- |
| CSP Lighthouse [Security Engineers] | 51d6186e-6489-4900-b93f-92e23144cca5      | Microsoft Sentinel Playbook Operator |Can list, view, and manually run playbooks|
| CSP Lighthouse [Security Engineers] | 3e150937-b8fe-4cfb-8069-0eaf05ecd056  | Microsoft Sentinel Responder |Can, in addition to the above, manage incidents (assign, dismiss, etc.)|
| CSP Lighthouse [Security Engineers] | ab8e14d6-4a74-4a29-9ba8-549422addade | Microsoft Sentinel Contributor|Can, in addition to the above, create and edit workbooks, analytics rules, and other Microsoft Sentinel resources.|
| CSP Lighthouse [Security Analysts] | 8d289c81-5878-46d4-8554-54e1e3d8b5cb   | Microsoft Sentinel Reader|Can view data, incidents, workbooks, and other Microsoft Sentinel resources.|
| CSP Lighthouse [Security Analysts] | 73c42c96-874c-492b-b04d-ab87d138a893   | Log Analytics Reader|Log Analytics Reader can view and search all monitoring data as well as and view monitoring settings, including viewing the configuration of Azure diagnostics on all Azure resources.|
| CSP Lighthouse [Security Analysts] | 3e150937-b8fe-4cfb-8069-0eaf05ecd056   | Microsoft Sentinel Responder|Can, in addition to the above, manage incidents (assign, dismiss, etc.)|
| Azure Security Insights | f4c81013-99ee-4d62-a7ee-b3f1f648599a | Microsoft Sentinel Automation Contributor |Allows Microsoft Sentinel to add playbooks to automation rules|
| CSP Lighthouse [Security Engineers] | 91c1777a-f3dc-4fae-b103-61d183457e46 | Managed Services Registration assignment Delete Role ||



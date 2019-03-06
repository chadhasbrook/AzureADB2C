# Impersonation Flow for Azure AD B2C
This is the files for a local account doing an impersonation flow for Azure AD B2C

## Common Scenarios
1. **Customer Service Representative** requires to assist a user and requires to log into the application on the behalf of the user. The CSR wants to see exactly what the user sees.
2. **Financial Investor** manages on the behalf of their customers. As such, a bank or an investment firm may require these individuals to log into their service/application to manage their customers information.

### Note:
A standard to manage impersonation flows is currently in development and has not been finalized. This sample does not reflect the final product or guidance. You should monitor on this progress and plan to make changes to your design as standards of the industry changes. You can read on it [here](https://tools.ietf.org/html/draft-ietf-oauth-token-exchange-10 "OAuth 2.0 Token Exchange draft-ietf-oauth-token-exchange-10").

## Disclaimer
The sample is developed and managed by the open-source community in GitHub. The application is not part of Azure AD B2C product and it's not supported under any Microsoft standard support program or service. The sample (Azure AD B2C policy and any companion code) is provided AS IS without warranty of any kind.

*Note: This sample policy is based on  [LocalAccounts](https://github.com/Azure-Samples/active-directory-b2c-custom-policy-starterpack/tree/master/LocalAccounts "LocalAccount Starter Pack") starter pack. All changes are marked with Demo: comment inside the policy XML files. Make the nessacery changes in the Demo action required sections.*
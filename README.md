# Integrate SSO Demo App as your App's SSO Authentication Flow
***The system is in TEST phase, and NOT to be used for production sites or by 3rd parties.***

### Prerequisites
- Application with OIDC SSO Flow Login (Web Application)
- A Domain to share and host your Application

## Steps
1. Contact support to initiate integration.
2. Follow instructions in the response to obtain relevant authentication/authorization APIs for your Application.
3. Add API endpoints in Application where necessary/relevant and use the decrypted keys as described in the support email response.
4. Once added share the domain name you intend to deploy your App and its authorization callback API (redirect_uri in client_secrets) path with support.
5. Wait for a response from support to cofirm integration and then continue to deploy and test the flow.

You should now have your App with the whole Sign-In/Up and SSO flow enabled with SSO Demo App as your authorization/authentication service!

Additional resources:
- Reach out to support for an example app that implements OIDC redirect flow to mimic your Application or use as a reference. The same steps should be followed in addition to the one's present in the codebase's README.

# port-crossplane

This repository will be used as a template for connecting Crossplane and Port through ArgoCD.

The following two secrets need to be set:

- `PORT_CLIENT_ID` - Your Port Client ID.
- `PORT_CLIENT_SECRET` - Your Port Client Secret.

Before triggering any PRs with ArgoCD, make sure the Action is allowed to create and merge PRs. This can be changed in the Settings under: **Code and automation | Actions | General | Workflow permissions**

<img width="872" alt="GitHub change Actions permission" src="https://github.com/user-attachments/assets/72a0e6e4-4dfe-45bd-8b36-3ec0efe2b845" />

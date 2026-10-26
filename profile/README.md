<picture>
  <source media="(prefers-color-scheme: dark)" srcset="logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="logo-light.svg">
  <img src="logo-light.svg" alt="ServerlessInbox" width="320">
</picture>

# ServerlessInbox

A complete serverless JMAP email server that runs in your own AWS account, for small companies already on AWS.

- **Install:** [docs.serverlessinbox.com](https://docs.serverlessinbox.com)
- **Issues:** [serverlessinbox/serverlessinbox](https://github.com/serverlessinbox/serverlessinbox/issues), the one place for every component
- **Questions and ideas:** [Discussions](https://github.com/orgs/serverlessinbox/discussions)

| Repo | What it is |
|---|---|
| [mailbox-cdk](https://github.com/serverlessinbox/mailbox-cdk) | CDK constructs, the infrastructure |
| [mailbox-idl](https://github.com/serverlessinbox/mailbox-idl) | JMAP JSON schemas, admin API protobuf, source of the generated SDKs |
| [artifact-registry](https://github.com/serverlessinbox/artifact-registry) | Release artifact resolution |

Public beta, provided as-is without warranty. Terms and status are in the [front-door README](https://github.com/serverlessinbox/serverlessinbox#readme).

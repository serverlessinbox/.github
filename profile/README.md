# ServerlessInbox

A complete serverless JMAP email server that runs in your own AWS account, for small companies already on AWS.

- **Install:** [docs.serverlessinbox.com](https://docs.serverlessinbox.com)
- **Issues and questions:** [serverlessinbox/serverlessinbox](https://github.com/serverlessinbox/serverlessinbox), the one place for every component

| Repo | What it is |
|---|---|
| [mailbox-cdk](https://github.com/serverlessinbox/mailbox-cdk) | CDK constructs, the infrastructure |
| [mailbox-apps](https://github.com/serverlessinbox/mailbox-apps) | Ready-to-deploy app / CloudFormation templates |
| [mailbox-idl](https://github.com/serverlessinbox/mailbox-idl) | JMAP JSON schemas, admin API protobuf, source of the generated SDKs |
| [jmap-server-go](https://github.com/serverlessinbox/jmap-server-go) | JMAP server library for Go |
| [admin-ui](https://github.com/serverlessinbox/admin-ui) | Admin frontend |
| [artifact-registry](https://github.com/serverlessinbox/artifact-registry) | Release artifact resolution |

Public beta, provided as-is without warranty. Terms and status are in the [front-door README](https://github.com/serverlessinbox/serverlessinbox#readme).

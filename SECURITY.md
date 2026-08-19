# Security Policy

## Supported Use

This repository is a historical lab reference asset. It is intended for disposable lab environments and should not be run against production controllers or production routers.

## Reporting Security Issues

If you find committed credentials, private keys, tokens, proprietary artifacts, or a workflow that could unexpectedly affect production systems, open a private security advisory or contact the repository maintainer through the project's preferred private reporting channel.

Do not publish exploit details, credentials, or live infrastructure identifiers in a public issue.

## Credential Handling

- Do not commit Postman environments, globals, `.env` files, API tokens, passwords, private keys, certificates, or controller credentials.
- Store lab credentials locally in Postman or another local secret store.
- Rotate any credential that was ever committed to a public fork or shared archive.
- Treat the collection's write and delete requests as privileged operations.

## Public Reference Guidance

Before publishing or sharing a fork, confirm that all variables, screenshots, exports, and diagrams are safe for the intended audience.

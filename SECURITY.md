# Security policy

MillionSend is email infrastructure — we take reports seriously and appreciate coordinated
disclosure.

## Reporting a vulnerability

**Please do not open a public issue.** Instead:

1. Use GitHub's private vulnerability reporting: on the affected repository, go to
   **Security → Report a vulnerability**. This is the preferred channel.
2. If that's not possible, email **security@millionsend.com**.

You'll get an acknowledgment within 72 hours. Please include reproduction steps and the
deployment type (cloud or self-hosted) where relevant.

## Scope

All repositories in the MillionSend organization. For self-hosted deployments, issues in
third-party dependencies (AWS SES, Postgres, etc.) should go to those projects — but if our
default configuration makes a dependency unsafe, that's ours and we want to know.

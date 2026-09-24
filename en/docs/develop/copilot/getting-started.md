---
title: "Getting Started"
description: Sign in to WSO2 Integrator Copilot with your WSO2 Cloud account or your own AI provider credentials.
keywords: [wso2 integrator, copilot, getting started, sign in]
slug: /develop/copilot/getting-started
---

# Getting Started

If you have already [signed in to WSO2 Integrator](../../get-started/setup/local-setup.md#step-4-sign-in-to-wso2-integrator) with your WSO2 Cloud account, WSO2 Integrator Copilot uses the same authentication and is ready to use. Otherwise, sign in from the Copilot welcome screen.

## Sign in from the Copilot welcome screen

1. Open your integration's overview and select the Copilot orb in the bottom-right corner. Select it once to open a quick chat, or double-click it to open the full Copilot panel. When a Ballerina file or diagram is open, you can also select the **Open WSO2 Integrator Copilot** icon in the editor toolbar.

   ![The WSO2 Integrator Copilot orb on the integration overview.](/img/develop/copilot/copilot-orb.png)

2. The Copilot panel opens on the welcome screen with the available sign-in options.

   ![WSO2 Integrator Copilot welcome screen with the sign-in options.](/img/develop/copilot/copilot-sign-in.png)

   - **Login using your WSO2 Cloud account** (recommended): Sign in with your WSO2 Cloud account. No API keys are required.
   - Under **Use your own AI provider**:
     - **Anthropic API Key**: Use your own [Anthropic API key](https://platform.claude.com/settings/keys) to power Copilot.
     - **AWS Bedrock**: Use your [AWS Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/getting-started.html) account.
     - **Google Vertex AI**: Use your [Google Vertex AI](https://docs.cloud.google.com/vertex-ai/docs/authentication) account.

3. Select one option and complete the sign-in. Once authenticated, Copilot opens its chat view and is ready to use.

   ![WSO2 Integrator Copilot signed in](/img/develop/copilot/copilot-welcome.png)

:::info Terms of use and data handling
By signing in, you agree to the WSO2 Integrator Copilot Terms of Use shown on the welcome screen. See [AI usage and data handling guidelines](../../reference/ai-usage-and-data-handling-guidelines.md) for how Copilot handles your data.
:::

## What's next

- [Copilot capabilities](overview.md) — Explore planning, review, testing, and more.

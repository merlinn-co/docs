---
sidebar_class_name: slack
---

# Slack

This guide shows you how to integrate Vespper with Slack.

## Overview

Vespper uses Slack in order to communicate with your team and help you resolve issues faster. This is the main
Vespper integration and it is mandatory. Moreover, Vespper uses its Slack permissions in order to retrieve historical and contextual data in real-time.

On the techical side, Vespper uses the standard OAuth flow to connect to Slack. For more information, check the [Slack documentation](https://api.slack.com/authentication/oauth-v2).

## Prerequisites

- Working environment with an organization. If you don't have one, head over to the [setup](../02-Getting%20started/01-Setup%20Vespper.md) page.

## Setup

Follow these steps to connect Vespper to Slack:

1. Inside your organization settings, go to "Integrations".
2. Locate the "Slack" integration and click "Add".
3. Inside the input field, insert your Slack Bot token. You can find it in your `.env` file or in the "OAuth & Permissions" screen inside your apps configuration page.

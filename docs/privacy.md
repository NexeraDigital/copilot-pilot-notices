---
layout: default
title: Privacy notice
permalink: /privacy/
---

# Nexera GIG Copilot Pilot — Privacy Notice

**Draft for Nexera review — not yet effective**  
Draft date: September 9, 2026  
Effective date: [Insert approved date]

## About this pilot

NexeraDigital operates this internal proof of concept to evaluate using Microsoft 365 Copilot to query GitHub work items and make requested test updates. The intended data sources are the NexeraDigital/GIGTestFY27 repository and NexeraDigital organization Project 18. This notice describes the pilot configuration; it does not cover other Nexera applications.

## Information processed and why

The pilot processes your questions, GitHub account identity, requested operations, GitHub results and generated answers to provide the requested assistance and evaluate whether the integration works correctly. Depending on the question, results can include issue titles and descriptions, comments, usernames and assignees, labels, dates, relationships, project fields and links. Work items can contain personal or confidential information even when stored in a test repository.

Information necessary for a query or requested update is sent to GitHub. Returned GitHub information is processed in Microsoft 365 Copilot to produce an answer. Changes that you authorize are sent to GitHub and may become visible to people with access to the affected work item.

## Sign-in and access

You use your Nexera Microsoft 365 account and separately authorize the GitHub OAuth application. Microsoft manages the OAuth connection and its tokens. Your GitHub password is entered with GitHub, not in the agent conversation. Do not put passwords, tokens or other secrets into prompts.

The application requests GitHub's `repo` and `project` permissions. These permissions are broader than read-only access to one test board and may permit access to other resources available to your GitHub account. The agent is instructed to stay within the pilot repository and board, but those instructions do not technically restrict the OAuth grant to those resources. GitHub permissions and organization policies still apply.

## Service providers and storage

Microsoft provides the Copilot and authentication services; GitHub provides the repository, project and API services. Their processing is subject to the applicable service agreements and Nexera's configuration. The current pilot has no separate Nexera-hosted application database or intermediary API service.

Copilot conversations and GitHub records may be retained by those services under their applicable settings. Nexera pilot administrators may collect test prompts, outputs, query documents, timestamps and error information to investigate failures and assess results. These records can contain information retrieved from GitHub. Access should be limited to personnel authorized to administer or evaluate the pilot.

Nexera pilot evidence retention: [Insert approved retention period and deletion process]. Microsoft 365 and GitHub retention requirements, including any applicable holds, may differ. Disconnecting the agent does not automatically delete previous conversations, test records or GitHub changes.

## Your choices and questions

You may stop using the pilot and revoke the OAuth application in GitHub under Settings → Applications → Authorized OAuth Apps. Contact the pilot administrator about access, retained records, corrections or deletion requests. Requests will be handled under applicable Nexera policies and service capabilities; removal of all retained copies is not guaranteed by revoking access.

Pilot contact: [Confirm responsible contact; proposed: rsmith@nexeradigital.com].

## Service documentation

- [Microsoft Copilot data, privacy and security](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-privacy)
- [GitHub: reviewing and revoking authorized OAuth apps](https://docs.github.com/en/apps/oauth-apps/using-oauth-apps/reviewing-your-authorized-oauth-apps)
- [GitHub OAuth permissions](https://docs.github.com/en/apps/oauth-apps/building-oauth-apps/scopes-for-oauth-apps)

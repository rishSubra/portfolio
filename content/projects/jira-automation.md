---
title: JIRA Time Tracking Automation
date: 2024-08-15
tags:
  - project
  - automation
  - python
  - aws
  - internship
description: Automated time tracking system using JIRA API and AWS Lambda
---

# JIRA Time Tracking Automation

*S3 Group Inc. (Aug 2024 - Dec 2024)*

Automated employee hour tracking system using Atlassian JIRA API and Activity Timeline API. Monitors activity patterns, identifies missing time logs, and sends personalized reminders.

## Architecture

**Script:** Python integration with JIRA REST API and Activity Timeline API

**Execution:** AWS Lambda for serverless scheduled jobs, EventBridge for cron scheduling

**Storage:** DynamoDB for historical data and employee patterns

**Notifications:** Amazon SES for personalized reminder emails

## Technical Approach

Implemented exponential backoff and caching to reduce JIRA API calls by 70% while staying within rate limits. Built timezone-aware scheduling using DynamoDB preferences and EventBridge rules for personalized reminder timing.

Designed smart reminder logic that learns employee logging patterns and detects discrepancies between JIRA activity and logged hours.

**Impact:** 40% improvement in on-time logging, 15 hours/week saved across management team.

---

[[projects/index|← Back to Projects]]

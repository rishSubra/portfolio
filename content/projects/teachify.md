---
title: Teachify
date: 2025-01-15
tags:
  - project
  - aws
  - machine-learning
  - internship
description: Cloud-native learning hub using AWS SageMaker to transform notes into study materials
---

# Teachify

*Nexus Technologies Group (Jan 2025 - May 2025)*

Cloud-native student learning hub that transforms unstructured notes into structured, interactive study content using AWS services and SageMaker Foundation models.

## Architecture

**Frontend:** AWS Amplify for hosting and backend integration

**Processing:** AWS Lambda for serverless execution, SageMaker Foundation models for content transformation

**Storage:** Amazon S3 for notes and generated content, DynamoDB for metadata

**Workflow:** Event-driven microservices with asynchronous processing via SQS and Step Functions

## Technical Approach

Designed batching and caching strategies to reduce SageMaker API calls by 60%, significantly lowering costs. Implemented async processing pipeline using SQS and Step Functions to handle large documents exceeding Lambda execution limits.

Presented weekly to engineering leadership on system architecture and SDLC. Demoed to AWS architects at their Atlanta office, receiving feedback on scalability.

---

[[projects/index|← Back to Projects]]

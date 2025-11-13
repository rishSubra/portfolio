---
title: Resumi
date: 2024-06-15
tags:
  - project
  - react-native
  - aws
  - machine-learning
  - mobile
description: Mobile app for student portfolios with ML-powered activity analysis
---

# Resumi

*Personal Project (June 2024 - Dec 2024)*

Mobile app for students to build portfolios of extracurricular activities and track academic performance. Features k-means clustering to analyze activity similarities and provide personalized insights.

## Architecture

**Frontend:** React Native for cross-platform mobile (iOS/Android), offline-first with local caching

**Backend:** GraphQL API via AWS AppSync with real-time sync, AWS Lambda for business logic

**Auth:** Amazon Cognito OAuth 2.0 for authentication and session management

**Database:** DynamoDB for scalable storage with optimistic UI updates

**ML:** k-means clustering algorithm (scikit-learn via Lambda) analyzing activity vectors based on type, time commitment, leadership level, and impact

## Technical Approach

Implemented AppSync subscriptions for real-time data sync across devices with optimistic UI updates for perceived performance. Built offline-first architecture with queue-based sync when connection restored.

Moved ML clustering to serverless Lambda functions to avoid resource-intensive operations on mobile devices, with result caching for fast retrieval.

---

[[projects/index|← Back to Projects]]

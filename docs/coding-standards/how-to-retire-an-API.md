---
title: How to retire an API
description: End-to-End Integration Testing and User Acceptance Testing
group: coding-standards
redirect_from: "/"
---

> TODO: Add Information yep

# API Lifecycle Workflow

```mermaid
sequenceDiagram
    participant API
    participant Developer

    Developer->>API: Develop Alpha version
    API-->>Developer: Alpha version ready

    Developer->>API: Develop Beta version
    API-->>Developer: Beta version ready

    Developer->>API: Develop Stable version
    API-->>Developer: Stable version ready

    Developer->>API: Deprecate API on 01/09/2020
    API-->>Developer: Deprecation notice issued

    Developer->>API: Develop Legacy version
    API-->>Developer: Legacy version ready

    Developer->>API: Retire API on 01/03/2022
    API-->>Developer: API retired

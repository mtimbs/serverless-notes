---
cover: >-
  https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=2970&q=80
coverY: 0
description: Pay per execution billing model
---

# Billing Model

**The lambda billing model impacts how we build things**

* cold starts
* runtime resources (memory + CPU)
* TypeScript/Node is perfect language for serverless (smaller bundles = faster loads)
* leverage front-end JS build tooling like esbuild/webpack to optimise bundle sizes
* push as much work async as possible to leverage batch processing and reduce execution times

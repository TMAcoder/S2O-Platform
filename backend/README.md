# Backend API – S2O Platform

This backend is the core API of the S2O-Platform, designed as a **multi-tenant SaaS system**
using **Flask Clean Architecture**.

## Responsibilities

- Provide REST APIs for Web and Mobile applications
- Handle authentication & authorization (JWT, RBAC)
- Support multi-tenant data isolation
- Manage restaurants, menus, orders, payments, and reviews
- Integrate AI modules (Chatbot QA & Recommendation Engine)

## Architecture

- Language: Python
- Framework: Flask
- Architecture: Clean Architecture (Domain – Service – Infrastructure – API)
- Database: PostgreSQL
- Cache & Realtime: Redis

> Source code will be implemented incrementally following Clean Architecture principles.

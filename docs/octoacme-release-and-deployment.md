# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## DevOps Engineer Responsibilities
DevOps Engineers are the primary owners of the deployment process. Their responsibilities include:
- Maintaining and executing CI/CD pipelines for all release types
- Provisioning and validating staging and production environments
- Coordinating deployment windows with Project Managers and QA Analysts
- Executing automated deployment scripts and monitoring rollout progress
- Leading rollback execution if a deployment fails or causes production impact
- Ensuring post-deploy monitoring and alerting is in place before declaring release complete

## Pre-release requirements
- All acceptance criteria met, PRs merged, and QA Analyst sign-off received
- Passing CI and security scans (validated by DevOps Engineer)
- Release notes drafted (Documentation Lead)
- Rollback / mitigation plan documented and reviewed with DevOps Engineer
- Smoke tests prepared and reviewed by QA Analyst

## Deployment Checklist
- [ ] Deployment window scheduled and communicated (Project Manager + DevOps Engineer)
- [ ] Backup or snapshot taken (DevOps Engineer, if applicable)
- [ ] Deploy to staging and run smoke tests (DevOps Engineer + QA Analyst)
- [ ] QA Analyst confirms staging sign-off before production deployment
- [ ] Deploy to production via automated pipeline (DevOps Engineer)
- [ ] Run post-deploy verifications (DevOps Engineer + QA Analyst)
- [ ] Release notes published (Documentation Lead)
- [ ] Announce release to stakeholders and support (Project Manager)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

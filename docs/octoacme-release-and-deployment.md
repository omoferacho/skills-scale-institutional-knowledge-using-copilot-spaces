# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by DevOps Engineer and Security Champion)
- QA/Test Lead has signed off on release readiness
- Release notes drafted and reviewed by Support Lead
- Rollback / mitigation plan documented (DevOps Engineer responsible)
- Smoke tests prepared and reviewed by QA/Test Lead

## Deployment Checklist
- [ ] Deployment window scheduled and communicated (PM + DevOps Engineer)
- [ ] Backup or snapshot (if applicable) — DevOps Engineer
- [ ] Deploy to staging and run smoke tests — DevOps Engineer + QA/Test Lead
- [ ] Security Champion confirms no outstanding critical vulnerabilities
- [ ] Deploy to production (automated pipeline preferred) — DevOps Engineer
- [ ] Run post-deploy verifications — DevOps Engineer + QA/Test Lead
- [ ] Announce release to stakeholders and support — PM + Support Lead

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer leads)
  - Rollback to last known-good release if necessary (DevOps Engineer)
  - Support Lead notifies customers of the impact and expected resolution
  - Security Champion assesses if the incident has security implications
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

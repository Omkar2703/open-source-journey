# 🚀 First Open Source Contribution

## Repository
parthbuilds-community/FitMart

## Issue
#361 Duplicate Google Fonts Import via Inline <style> in Every Component

## Date
10 June 2026

## Problem
Multiple components and pages imported Google Fonts individually, causing redundant font requests and making font management harder.

## Changes Made
- Removed duplicate Google Fonts imports.
- Kept a single import inside src/index.css.
- Preserved existing styles and UI.

## Challenges Faced
### Dependency conflicts
- Vite vs @vitejs/plugin-react
- ESLint version mismatch

### Environment setup
- Missing .env
- Firebase auth/invalid-api-key

### Git setup
- Configuring username and email

## What I Learned
- Fork → Clone → Branch → Commit → Push → PR workflow.
- Reading and understanding GitHub issues.
- Debugging dependency problems.
- Creating a clean Pull Request.

## Pull Request
(Add your PR URL here after it is created.)

## Status
✅ Submitted first open source PR 🎉
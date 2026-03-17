# dress-guide

AI outfit guidance project for WeChat Mini Program.

## Overview

This repository contains:
- Prototype pages from `dressguide.html` (now under `docs/`)
- System architecture design for the AI outfit recommendation app

## Project Structure

- `docs/ai-dress-guide-architecture.md`: full architecture design
- `docs/dressguide.html`: interactive prototype HTML
- `.env.example`: environment variable template
- `CONTRIBUTING.md`: contribution workflow and guardrails

## Core Goals

- Generate daily outfit recommendations based on weather and wardrobe
- Keep outfit choices temperature-appropriate
- Consider color and style matching
- Support wardrobe management and recommendation history

## Project Conventions

- Copy `.env.example` to your local env file before running services
- Follow branch naming and commit conventions in `CONTRIBUTING.md`
- Do not commit real secrets

## Status

Current repository baseline is documentation-first.
Implementation of mini program and backend services can follow this design.

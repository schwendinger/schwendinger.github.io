# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Sandbox / toy project hosted on GitHub Pages. Each subfolder is an independent mini project. There is no build system, bundler, or package manager.

## Deployment

Push to `master` → auto-deploys via GitHub Pages. Pages are accessible at `https://schwendinger.github.io/<path>`.

## Conventions

- Each mini project lives in its own subfolder with an `index.html` entry point
- Projects are self-contained — no shared framework or dependencies between them
- Static HTML/CSS/JS only (no build step)
- **This is a public repository — NEVER commit secrets, API keys, tokens, or credentials**

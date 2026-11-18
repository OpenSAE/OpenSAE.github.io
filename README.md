# OpenSAE website

[English](README.md) | [中文](README.zh-CN.md)

## Purpose

This repository maintains the [OpenSAE website](https://opensae.github.io/) and its research pages, SAEBase workspace, public Atlas snapshots, and demonstration data.

## Scope

Use this repository to maintain and deploy the organization's public static website. Each research repository maintains its own methods and tutorials.

## Publishing

GitHub Pages deploys the website after changes reach `main`. The deployment checks the SAEBase and OpenResearch Atlas snapshots before publishing.

For a SAEBase Atlas update, run **Prepare SAEBase Atlas snapshot** with the full SHA of the SAEBase commit containing the generator. Review the resulting artifact and replace `saebase/atlas/` with it, including removal of outdated generated files. Submit the snapshot change to this repository. The existing SAEBase snapshot records its source commit in `saebase/atlas/site-manifest.json`. For OpenResearch, use `openresearch/atlas/` to submit an approved public snapshot from its maintainers.

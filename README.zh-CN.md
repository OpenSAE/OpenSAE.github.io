# OpenSAE 官网

[English](README.md) | [中文](README.zh-CN.md)

## 目的和主要功能

本仓库维护 [OpenSAE 官网](https://opensae.github.io/)，包括研究页面、SAEBase 工作区、公开 Atlas 快照和演示数据。

## 适用范围

维护或部署 OpenSAE 组织的公开静态网站时使用。研究方法和教程由各研究仓库维护。

## 发布

变更进入 `main` 后，GitHub Pages 部署官网。部署过程先检查 SAEBase 和 OpenResearch 的 Atlas 快照。

更新 SAEBase Atlas 时，运行 **Prepare SAEBase Atlas snapshot**，填写包含生成程序的 SAEBase 源码提交的完整 SHA。审阅生成的产物后，用它替换 `saebase/atlas/`，移除过时的生成文件，再提交变更。现有 SAEBase 快照的源码提交记录在 `saebase/atlas/site-manifest.json`。更新 OpenResearch Atlas 时，将维护者审定的公开快照提交至 `openresearch/atlas/`。

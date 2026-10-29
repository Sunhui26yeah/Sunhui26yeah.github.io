---
title: "From GPU to TPU with Coding Agents: What Works, What Fails, and What It Costs?"
collection: publications
category: manuscripts
permalink: /publication/2026-gpu-to-tpu-coding-agents
excerpt: 'An empirical study of using Claude Code to migrate ten PyTorch ML research projects from NVIDIA GPUs to Google Cloud TPUs, assessing whether each migration runs, preserves numerical behavior, executes on the intended hardware, keeps the project goal, and performs acceptably. Currently under review.'
date: 2026-10-25
venue: 'International Conference on Software Engineering, Software Engineering in Practice (ICSE-SEIP 2027) — Under Review'
paperurl: 'https://arxiv.org/abs/2610.34422'
citation: 'Hui Sun, Anderson Uchôa, and Wesley K. G. Assunção. &quot;From GPU to TPU with Coding Agents: What Works, What Fails, and What It Costs?&quot; arXiv:2610.34422, 2026. [Under Review at ICSE-SEIP 2027]'
---
A coding agent can migrate a machine learning workload, report success, and still change how the model trains. Rising compute costs, limited accelerator capacity, and vendor dependence are pushing organizations toward alternatives to graphics processing units (GPUs); a key question is whether agent-generated migrations to tensor processing units (TPUs) can be trusted and at what cost. We build a dataset of 148 PyTorch ML research projects and use Claude Code to migrate ten of them from NVIDIA GPUs to Google Cloud TPUs. We independently assess whether each migration runs, preserves numerical behavior, executes on the intended hardware, maintains the project's goal, and delivers acceptable performance. We also examine failures, human effort, and costs. Eight projects meet our project-goal criterion, and migrations require 2.4 human interventions on average. Of 70 execution attempts, 53 fail (76%), and 26 of these failures (49%) raise no error. The most frequent cause is repeated compilation and other execution inefficiencies, while interactions with third-party libraries can silently change the computation: in one four-chip migration, the agent reports success despite a change in gradient clipping that reduces accuracy from 86.53% to 84.89%. Execution costs vary widely: in one workload, TorchTPU, a PyTorch execution backend for TPUs, trains 1.86 times faster and 25% cheaper per run than the GPU. For practitioners, these findings motivate independent reference runs, verification under the intended hardware configuration, and workload-specific acceptance and stopping criteria that account for both computational and human costs.

[Read on arXiv](https://arxiv.org/abs/2610.34422)

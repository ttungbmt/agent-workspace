# Agent Workspace

> A unified workspace for AI-assisted software development.

Agent Workspace is a platform for creating, standardizing, and managing AI development environments across different coding tools and agent runtimes.

The goal is simple: make AI coding environments easier to set up, easier to reproduce, and easier to govern.

Instead of manually configuring every tool, plugin, skill, MCP, command, or runtime, Agent Workspace provides a common layer that describes how an AI development environment should look and keeps that environment consistent across projects and machines.

## Why

AI coding tools are becoming increasingly capable, but their ecosystems are fragmented.

Each runtime has its own configuration model, extension format, installation flow, and conventions. As the number of tools grows, maintaining a consistent development environment becomes difficult.

Agent Workspace provides a common abstraction above those ecosystems.

```text
                    Agent Workspace

                         Workspace
                            │
                ┌───────────┼───────────┐
                │           │           │
             Sources     Policies    Profiles
                │           │           │
                └───────────┼───────────┘
                            │
                         Resolver
                            │
                         Adapters
            ┌───────────────┼───────────────┐
            │               │               │
       Claude Code        Codex        Other Runtimes
```

## Philosophy

Agent Workspace is not another collection of AI coding plugins.

It is a management layer for the environment around them.

The project is built around a few principles:

- **Declare, don't manually configure**
- **One model, multiple runtimes**
- **Reproducible environments**
- **Composable instead of monolithic**
- **User-owned configuration**
- **Tool-independent architecture**

## Vision

An AI development environment should be as easy to reproduce as a modern development toolchain.

You should be able to describe your preferred workspace once and use it across projects, machines, teams, and AI coding runtimes.

Agent Workspace aims to become that common layer.

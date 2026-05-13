# Server [ GO [Gorilla] ]

### Table of Contents

[Libraries](#libraries)

[Go Workspaces](#go-workspaces)

Authentication

Payment

API Documentation

CI/CD

[NOTE](#note)

# Libraries

## Router - Gorilla

### Installation

```go
go get github.com/gorilla/mux
```

## Logging - Zap

### Installation

```go
go get -u go.uber.org/zap
```

## Live Reloading - Air

### Installation

```go
go install github.com/air-verse/air@latest
```

Docs -[ https://github.com/air-verse/air/](https://github.com/air-verse/air/)

# Authentication

Resources : [Authentication Types and Techniques - Medium.com - Aly Ragab](https://medium.com/@alyragab70/authentication-types-and-techniques-eb8232eebcfb)

The template uses OAuth authentication with Google, and Github preimplemented, to implement other OAuth flow follow official docs from the providers website. Also implementation of JWT ( JSON Web Tokens ), Magiclink, and SSO ( Single Sign On ) is available in the `auth` module.

# Payment

Razor pay integration is available for payment processing, and validation.

# API Documentation - Swaggo

# Linting - Golangci-lint

# Remote Repository Config

## GitHub

## GitLab

# Go workspaces

Resources : [Go Workspaces: Simplifying Mutli-Modular Projects - Medium.com - Sabbir Ahmed](https://bysabbir.medium.com/go-workspaces-simplifying-multi-modular-projects-dc1a489302a) | [Tutorial: Getting started with multi-module workspaces](https://go.dev/doc/tutorial/workspaces)

# NOTE

AGENTS.md - is a copy of the go best practices for agentic development used in the [Air](https://github.com/air-verse/air) project by [air-verse](https://github.com/air-verse).

All git commit messages must follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for both human and machine readable.

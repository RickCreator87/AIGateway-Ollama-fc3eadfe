# AI Gateway for Ollama

An OpenAI API–compatible gateway that proxies requests to a local Ollama instance.

This project lets you run local LLMs via Ollama while keeping compatibility with tools and SDKs built for the OpenAI API.

---

## What This Does

- Exposes OpenAI-style endpoints (`/v1/chat/completions`)
- Forwards requests to Ollama
- Uses API keys to select models and behavior
- Runs locally via Docker or directly with Python

If a client works with `api.openai.com`, it should work here with minimal or zero changes.

---

## Architecture (High Level)

[![Maintainability](https://qlty.sh/gh/RickCreator87/projects/rickcreator87.github.io/maintainability.svg)](https://qlty.sh/gh/RickCreator87/projects/rickcreator87.github.io)

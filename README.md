# Accord Project MCP Experiment 🚀

This repository contains a **Proof-of-Concept MCP (Model Context Protocol) Server** built as part of my application for **Google Summer of Code 2026**.

## 🎯 Goal
The goal of this experiment is to demonstrate the integration of Accord Project template management logic with the Model Context Protocol, allowing LLMs (like Claude) to interact with smart legal contracts.

## 🛠️ Tech Stack
- **Language:** TypeScript
- **Framework:** @modelcontextprotocol/sdk
- **Runtime:** Node.js

## 🚀 Features implemented in this PoC
1. **Resources:** Exposing `accord://templates/` as queryable resources for LLMs.
2. **Tools:** A `validate_contract` tool that allows an agent to check contract text against Concerto models.
3. **Transport:** Standard JSON-RPC over `stdio`.

## 📦 How to run
1. Install dependencies:
   ```bash
   npm install
   ```
2. Build the project:
   ```bash
   npx tsc
   ```
3. Run the server:
   ```bash
   node build/index.js
   ```

---
*Created by Aliaksei Ioda for GSoC 2026.*

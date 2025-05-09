# 🌤️ MCP Weather Server (TypeScript)

A modern weather server built with the [Model Context Protocol (MCP)](https://modelcontextprotocol.org/) using the **TypeScript SDK**. This project exposes real-time weather forecast and alert tools for integration with LLM clients like **Claude for Desktop**.

---

## 📌 Features

- `getAlerts(state: string)`: Get real-time weather alerts by U.S. state.
- `getForecast(latitude: number, longitude: number)`: Get short-term forecasts by coordinates.
- Built using **TypeScript MCP SDK**.
- Async HTTP requests powered by **Axios**.
- Compatible with Claude for Desktop and other MCP-enabled clients.

---

## ⚙️ Tech Stack

- **Node.js v18+**
- **TypeScript**
- **MCP SDK (TypeScript)** – [`@mcp/sdk`](https://www.npmjs.com/package/@mcp/sdk)
- **Axios** – HTTP client
- **weather.gov API** – U.S. National Weather Service

---

## 🚀 Quickstart

### 1. Clone the repository

```bash
git clone https://github.com/your-username/mcp-weather-server-ts.git
cd mcp-weather-server-ts

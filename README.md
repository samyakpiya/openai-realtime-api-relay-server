# OpenAI Realtime API Relay Server

A simple relay server for the OpenAI Realtime API that allows you to:

- Hide API credentials when deploying applications
- Handle sensitive instruction calls on the server
- Restrict which events clients can send and receive
- Manage WebSocket connections between clients and the OpenAI Realtime API

## Getting Started

1. Clone this repository
2. Create a `.env` file with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the relay server:
   ```bash
   npm start
   ```
   Or for development with auto-reload:
   ```bash
   npm run dev
   ```
5. The server will start on port 8081 by default. You can change this by setting the `PORT` environment variable in your `.env` file.

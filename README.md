# Secure Messaging Application

A secure messaging project with encrypted message payloads and signature verification patterns across a React client and Node.js backend.

## What this project demonstrates

- AES encryption/decryption flow for messages
- RSA-style signature generation and verification flow (`node-forge`)
- Real-time chat-oriented UX with user/group conversation views
- MongoDB-backed message/user/group persistence

## Tech Stack

- Frontend: React
- Backend: Node.js + Express
- Database: MongoDB + Mongoose
- Security libraries: `crypto`, `crypto-js`, `node-forge`

## Repository Structure

- `client/` - React frontend
- `server/` - API routes, models, and crypto/signature logic

## Run Locally

### Client

```bash
cd client
npm install
npm start
```

### Server

```bash
cd server
npm install
npm start
```

## Note

This repository currently uses JavaScript for the app stack. If you want your CV line to say Python here, that claim should be revised or backed by Python components in this repo.

# Consumer–Provider Handshake

## Thông tin chung

- Lab: FIT4110 Lab 03
- Ngày: 2026-05-20
- Provider team: Team 08 (IoT Ingestion - B1)
- Consumer team: Team B6 (Core Business)
- Provider service: IoT Ingestion Service
- Consumer service: Core Business Service

## Contract

- Contract file: `contracts/iot-ingestion.openapi.yaml`
- Mock base URL: `http://localhost:4010`
- Auth method: Bearer Token (JWT)
- Endpoint được test: `POST /api/v1/telemetry`, `GET /api/v1/telemetry`, `GET /health`

## Smoke test

### Request

```http
POST /api/v1/telemetry
Authorization: Bearer lab-token
Content-Type: application/json
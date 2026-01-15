# Health Promotion LINE Official Account – Webhook & Flex Integration

## Overview

| Item | Description |
|------|-------------|
| Project | Health Promotion LINE Official Account |
| Organization | Kamphaeng Phet Community Municipal Hospital |
| Purpose | Support LINE OA broadcasts, Flex Messages, and backend messaging |
| Role | Integration between LINE Messaging API and backend systems |

---

## Module Focus

| Area | Description |
|------|-------------|
| Webhook Endpoint | Receives and handles LINE events |
| Flex Messaging | Sends structured personalized messages |
| Broadcasts | Scheduled and campaign messaging |
| Resources | Health promotion content and schedules |

---

## Architecture Layers

| Layer | Responsibility |
|-------|--------------|
| Interface | HTTP webhook endpoint |
| Event Processing | Validates and dispatches LINE events |
| Flex Engine | Constructs and sends Flex Messages |
| Backend API | Integrates with hospital services |

---

## Event Flow

| Step | Description |
|------|-------------|
| 1 | LINE triggers webhook event |
| 2 | Validate request using channel secret |
| 3 | Dispatch to event processor |
| 4 | Execute broadcast or Flex message action |
| 5 | Send response via LINE Messaging API |

---

## Configuration

| Variable | Purpose |
|----------|---------|
| LINE_CHANNEL_SECRET | Validate webhook calls |
| LINE_CHANNEL_TOKEN | API access |
| BROADCAST_API_URL | Backend broadcast API |
| FLEX_TEMPLATE_PATH | Flex message definitions |

---

## Deployment

| Requirement | Detail |
|-------------|--------|
| Protocol | HTTPS |
| Hosting | Cloud or on-premise |
| Monitoring | Logging & alerting |

---

## Usage

This system is for official use by hospital health promotion teams only.

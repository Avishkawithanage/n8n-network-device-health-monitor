# Network Device Health Monitor (n8n)

## Overview
This project is an automated network/device health monitoring system built using n8n.
It periodically checks service availability and sends real-time Telegram alerts when downtime is detected.

## Workflow Logic
- Schedule Trigger runs every 5 minutes
- HTTP Request checks service availability
- IF condition evaluates status
- Alert is sent only when the service is DOWN

## Features
- Automated monitoring
- Failure-only alerting
- Telegram Bot integration
- No paid services required

## Technologies Used
- n8n
- HTTP Monitoring
- Telegram Bot API

## Setup Instructions
1. Import the workflow JSON into n8n
2. Configure Telegram credentials (Bot Token, Chat ID)
3. Activate the workflow

   Security Note:
This repository does not include any credentials.
Telegram Bot Token and Chat ID must be configured manually
after importing the workflow into n8n.


## Author
Avishka Withanage

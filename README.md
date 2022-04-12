# Uptime-Monitoring-RESTful-API-Server
Uptime Monitoring RESTful API Server that allows authenticated users to monitor URLs, and get detailed uptime reports about their availability, average response time, and total uptime/downtime.

# Overview
- Signup with email verification.
- CRUD operations for URL checks (GET, PUT and DELETE can be called only by the user user who created the check).
- Authenticated users can receive a notification whenever one of their URLs goes down or up again: Email. Webhook (optional).
- Authenticated users can get detailed uptime reports about their URLs availability, average response time, and total uptime/downtime.
- Authenticated users can group their checks by tags and get reports by tag.

# PrismEdgeTracker

PrismEdgeTracker monitors edge-originated logs in real-time and scores events based on anomaly weight. Ideal for security and behavioral insight in distributed systems.

## Features
- Edge log aggregation with minimal delay.
- Heuristic scoring of events.
- Notification hooks via email and webhook.
- Can be embedded into CDN or reverse proxy stack.

## Usage
```bash
git clone https://github.com/your-org/PrismEdgeTracker.git
cd PrismEdgeTracker
python tracker/main.py edge_logs.json

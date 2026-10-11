# Final Pool of Implemented Tasks

This directory collects every task marked **implemented** in the Notion **Task Tracker → Task Status Table** at the time of this consolidation.

- Source: `toolathlon/BenchTasksCollv3`, each developer branch at its latest commit.
- Each task is copied verbatim to `tasks/finalpool/<task-name>/`, preserving its internal layout (`docs/`, `evaluation/`, `preprocess/`, `initial_workspace/`, `groundtruth_workspace/`).
- Total: **79 implemented tasks** from 14 developers (397 files).
- `manifest.json` lists `[task name, implementing developer, source commit]` for every task.
- Tasks still marked `implementing` in the tracker are deliberately excluded.

## Acceptance check

Based on `tasks/examples/example-task`:

- `docs/task.md` and `docs/agent_system_prompt.md` must exist, be non-empty and be entirely English (no Chinese).
- `docs/user_system_prompt.md` is optional; when present and non-empty it must be entirely English.
- `evaluation/main.py`, `preprocess/main.py`, `initial_workspace/` and `groundtruth_workspace/` are optional; only their existence is checked when present.

## Tasks by developer

### fan-dev (4)
- `coupon-manager`
- `discount-calculator`
- `loyalty-program`
- `price-tracker`

### gyy (7)
- `blog-engine`
- `cms-builder`
- `content-scheduler`
- `robots-handler`
- `sitemap-generator`
- `social-publisher`
- `tag-manager`

### haoze (4)
- `media-organizer`
- `streaming-service`
- `subtitle-generator`
- `video-trimmer`

### jl_dev (5)
- `canvas-grade-automation`
- `customer-feedback-processor`
- `email-classification-system`
- `inventory-management`
- `pdf-report-generator`

### junteng_dev (9)
- `booking-system`
- `calendar-sync`
- `contact-manager`
- `customer-portal`
- `help-desk`
- `order-processor`
- `product-catalog`
- `reminder-service`
- `shipment-tracker`

### junxian_dev (3)
- `qr-generator`
- `social-connector`
- `translation-api`

### lueyang-dev (8)
- `activity-logger`
- `client-portal`
- `crm-system`
- `deal-manager`
- `email-campaign`
- `follow-up-reminder`
- `sales-pipeline`
- `territory-manager`

### lv (7)
- `analytics-dashboard`
- `chat-bot`
- `feedback-collector`
- `personalization-service`
- `sentiment-analyzer`
- `survey-builder`
- `voice-processor`

### ruige (6)
- `canvas-automation`
- `data-analytics`
- `expense-tracker`
- `file-manager`
- `log-analyzer`
- `web-crawler`

### wenshuo-dev (4)
- `cache-optimizer`
- `image-processor`
- `scheduler`
- `search-engine`

### xiaochen_dev (7)
- `backup-utility`
- `deployment-tool`
- `error-tracker`
- `health-monitor`
- `monitoring-agent`
- `security-scanner`
- `status-checker`

### yuxuan-dev (5)
- `asset-optimizer`
- `content-manager`
- `network-analyzer`
- `sync-service`
- `task-scheduler`

### yuzhen-dev (6)
- `alert-system`
- `data-validator`
- `form-builder`
- `invoice-generator`
- `payment-processor`
- `permission-manager`

### zhaochen (4)
- `certificate-manager`
- `load-balancer`
- `storage-manager`
- `template-engine`

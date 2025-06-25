# Project deployment configuration

General info:
```
URL=https://n8n.dkmedia.si 
APP_NAME=n8n-dkmedia
```

N8N configuration:
```
N8N_HOST="https://n8n.dkmedia.si"
N8N_EDITOR_BASE_URL="https://n8n.dkmedia.si"
WEBHOOK_URL="https://n8n.dkmedia.si"
N8N_PROTOCOL="https"
N8N_PORT="5678"
GENERIC_TIMEZONE="UTC"
N8N_EMAIL_MODE="smtp"
EXECUTIONS_DATA_PRUNE="true"
N8N_USER_FOLDER="/home/node/data"
N8N_RUNNERS_ENABLED="true"
N8N_ENFORCE_SETTINGS_FILE_PERMISSIONS="true"
EXECUTIONS_DATA_MAX_AGE="168"
EXECUTIONS_DATA_PRUNE_MAX_COUNT="1000"
EXECUTIONS_DATA_SAVE_ON_SUCCESS="none"
EXECUTIONS_DATA_SAVE_ON_ERROR="all"
EXECUTIONS_DATA_SAVE_ON_PROGRESS="false"

N8N_ENCRYPTION_KEY={ENCRYPTION_KEY}
```

Github Actions - Repository Secrets:
```
FLY_APP_NAME="n8n-dkmedia"
FLY_API_TOKEN="{API_TOKEN}
```
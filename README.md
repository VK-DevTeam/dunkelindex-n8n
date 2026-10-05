# n8n on Render

Workflow automation hosted on Render.com

## Setup

1. Push to GitHub
2. Connect repository to Render
3. Set environment variables in Render dashboard:
   - `WEBHOOK_URL`: Your custom domain URL (e.g., `https://n8n.yourdomain.com`)
   - `N8N_BASIC_AUTH_USER`: Your admin username
   - `N8N_BASIC_AUTH_PASSWORD`: Your admin password
4. Deploy
5. Add custom domain in Render settings

## Importing Workflows

Once deployed, import `Dunkel Index Premium Picks.json` through the n8n UI:
- Workflows → Import from File

## Notes

- For production, configure PostgreSQL database connection
- Update `WEBHOOK_URL` after adding custom domain

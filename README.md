# comment-bot

#### Trigger by doing

```bash
curl \
  -X POST \
  -H "Accept: application/vnd.github.v3+json" \
  -u [Username]:[Personal Access Token] \
  https://api.github.com/repos/JayjeetAtGithub/comment-bot/dispatches \
  -d '{  "event_type": "run", "client_payload": {"ref": "261"} }'
```

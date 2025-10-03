# BEAR MCP POC: YAML Phraser & Doc Classifier

This repo contains a minimal MCP-style POC server (FastAPI) that exposes:
- /tools/list
- /tools/call (doc_classifier, yaml_phraser)
- Safety checks: invention detection, provenance hashing, S3 audit logging, Postgres audit stub

Next steps:
1. Deploy to Render (connect this repo).
2. Add `API_KEY`, `S3_BUCKET`, `DATABASE_URL` as Render environment variables.
3. Test /tools/list and /tools/call with curl or Postman.

See file `mcp_poc_server.py` for implementation details.# bear-mcp-poc-
POC: MCP-style YAML phraser + doc classifier for BEAR Apps

---
name: anaplan-run-export
description: Run an Anaplan export action and download the exported file chunks via the Integration API v2.0.
api: Anaplan API
generated: '2026-10-20'
method: generated
source: openapi/_ae-authored/anaplan-openapi-generated.yml
operations:
- get_2_0_workspaces
- get_2_0_workspaces_workspaceid_models
- get_2_0_workspaces_workspaceid_models_modelid_exports
- post_2_0_workspaces_workspaceid_models_modelid_exports_exportid_tasks
- get_2_0_workspaces_workspaceid_models_modelid_exports_exportid_tasks_taskid
- get_2_0_workspaces_workspaceid_models_modelid_files_fileid_chunks
- get_2_0_workspaces_workspaceid_models_modelid_files_fileid_chunks_chunkid
---
Grounded in a contract GENERATED from Anaplan's documentation (not published by Anaplan).

1. Authenticate with the Authentication Service API and send `Authorization: AnaplanAuthToken {token}`.
2. List workspaces, then models, then the model's exports to find `exportId`.
3. POST a task to the export; poll the task by `taskId` until it completes.
4. List the export file's chunks (the file id equals the export id) and GET each chunk in order.

Rules: no idempotency key exists — each POST starts a new task, so do not retry blindly. A 429 means back off (no numeric limit is published).


# Test project

This is a test project created by ApiLogicServer.  It explores various approaches to grants that are global - apply to all tables, eg:

* multi-tenant - each table has `Client_id`; filter in this from users' row

* soft delete - don't show rows where `is_deleted == True`
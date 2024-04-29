# gitlab_ce Integration

This integration is for ingesting data from [gitlab_ce](https://example.com/).

- `production`: Collect logs for Rails controller requests received from GitLab.

See [Link to docs](https://example.com/docs) for more information.

## Compatibility

Insert compatibility information here. This could for example be which versions of the product it was tested with.

## Setup

Insert how to configure the vendor side of the integration here, for example how to configure the API, create a syslog remote destination etc.

## Logs

### production

Insert a description of the data stream here.

**Exported fields**

| Field | Description | Type |
|---|---|---|
| @timestamp | Event timestamp. | date |
| cloud.image.id | Image ID for the cloud instance. | keyword |
| container.labels | Image labels. | object |
| data_stream.dataset | Data stream dataset name. | constant_keyword |
| data_stream.namespace | Data stream namespace. | constant_keyword |
| data_stream.type | Data stream type. | constant_keyword |
| event.dataset | Event dataset | constant_keyword |
| event.module | Event module | constant_keyword |
| gitlab_ce.production.controller |  | keyword |
| gitlab_ce.production.cpu_s |  | long |
| gitlab_ce.production.db_cached_count |  | long |
| gitlab_ce.production.db_ci_cached_count |  | long |
| gitlab_ce.production.db_ci_count |  | long |
| gitlab_ce.production.db_ci_duration_s |  | long |
| gitlab_ce.production.db_ci_replica_cached_count |  | long |
| gitlab_ce.production.db_ci_replica_count |  | long |
| gitlab_ce.production.db_ci_replica_duration_s |  | long |
| gitlab_ce.production.db_ci_replica_txn_count |  | long |
| gitlab_ce.production.db_ci_replica_txn_duration_s |  | long |
| gitlab_ce.production.db_ci_replica_wal_cached_count |  | long |
| gitlab_ce.production.db_ci_replica_wal_count |  | long |
| gitlab_ce.production.db_ci_txn_count |  | long |
| gitlab_ce.production.db_ci_txn_duration_s |  | long |
| gitlab_ce.production.db_ci_wal_cached_count |  | long |
| gitlab_ce.production.db_ci_wal_count |  | long |
| gitlab_ce.production.db_count |  | long |
| gitlab_ce.production.db_duration_s |  | long |
| gitlab_ce.production.db_main_cached_count |  | long |
| gitlab_ce.production.db_main_count |  | long |
| gitlab_ce.production.db_main_duration_s |  | long |
| gitlab_ce.production.db_main_replica_cached_count |  | long |
| gitlab_ce.production.db_main_replica_count |  | long |
| gitlab_ce.production.db_main_replica_duration_s |  | long |
| gitlab_ce.production.db_main_replica_txn_count |  | long |
| gitlab_ce.production.db_main_replica_txn_duration_s |  | long |
| gitlab_ce.production.db_main_replica_wal_cached_count |  | long |
| gitlab_ce.production.db_main_replica_wal_count |  | long |
| gitlab_ce.production.db_main_txn_count |  | long |
| gitlab_ce.production.db_main_txn_duration_s |  | long |
| gitlab_ce.production.db_main_wal_cached_count |  | long |
| gitlab_ce.production.db_main_wal_count |  | long |
| gitlab_ce.production.db_primary_cached_count |  | long |
| gitlab_ce.production.db_primary_count |  | long |
| gitlab_ce.production.db_primary_duration_s |  | long |
| gitlab_ce.production.db_primary_txn_count |  | long |
| gitlab_ce.production.db_primary_txn_duration_s |  | long |
| gitlab_ce.production.db_primary_wal_cached_count |  | long |
| gitlab_ce.production.db_primary_wal_count |  | long |
| gitlab_ce.production.db_replica_cached_count |  | long |
| gitlab_ce.production.db_replica_count |  | long |
| gitlab_ce.production.db_replica_duration_s |  | long |
| gitlab_ce.production.db_replica_txn_count |  | long |
| gitlab_ce.production.db_replica_txn_duration_s |  | long |
| gitlab_ce.production.db_replica_wal_cached_count |  | long |
| gitlab_ce.production.db_replica_wal_count |  | long |
| gitlab_ce.production.db_txn_count |  | long |
| gitlab_ce.production.db_write_count |  | long |
| gitlab_ce.production.format |  | keyword |
| gitlab_ce.production.graphql.complexity |  | long |
| gitlab_ce.production.graphql.depth |  | long |
| gitlab_ce.production.graphql.operation_name |  | keyword |
| gitlab_ce.production.location |  | keyword |
| gitlab_ce.production.mem_bytes |  | long |
| gitlab_ce.production.mem_mallocs |  | long |
| gitlab_ce.production.mem_objects |  | long |
| gitlab_ce.production.mem_total_bytes |  | long |
| gitlab_ce.production.meta.caller_id |  | keyword |
| gitlab_ce.production.meta.client_id |  | keyword |
| gitlab_ce.production.meta.feature_category |  | keyword |
| gitlab_ce.production.meta.remote_ip |  | keyword |
| gitlab_ce.production.meta.search.page |  | keyword |
| gitlab_ce.production.meta.user |  | keyword |
| gitlab_ce.production.meta.user_id |  | long |
| gitlab_ce.production.params.key |  | keyword |
| gitlab_ce.production.params.param_value |  | keyword |
| gitlab_ce.production.params.value |  | keyword |
| gitlab_ce.production.params.value_json.operationName |  | keyword |
| gitlab_ce.production.params.value_json.query |  | keyword |
| gitlab_ce.production.params.value_json.variables |  | keyword |
| gitlab_ce.production.queue_duration_s |  | long |
| gitlab_ce.production.redis_allowed_cross_slot_calls |  | long |
| gitlab_ce.production.redis_cache_calls |  | long |
| gitlab_ce.production.redis_cache_duration_s |  | long |
| gitlab_ce.production.redis_cache_read_bytes |  | long |
| gitlab_ce.production.redis_cache_write_bytes |  | long |
| gitlab_ce.production.redis_calls |  | long |
| gitlab_ce.production.redis_db_load_balancing_calls |  | long |
| gitlab_ce.production.redis_db_load_balancing_duration_s |  | long |
| gitlab_ce.production.redis_db_load_balancing_write_bytes |  | long |
| gitlab_ce.production.redis_duration_s |  | long |
| gitlab_ce.production.redis_feature_flag_calls |  | long |
| gitlab_ce.production.redis_feature_flag_duration_s |  | long |
| gitlab_ce.production.redis_feature_flag_read_bytes |  | long |
| gitlab_ce.production.redis_feature_flag_write_bytes |  | long |
| gitlab_ce.production.redis_read_bytes |  | long |
| gitlab_ce.production.redis_sessions_allowed_cross_slot_calls |  | long |
| gitlab_ce.production.redis_sessions_calls |  | long |
| gitlab_ce.production.redis_sessions_duration_s |  | long |
| gitlab_ce.production.redis_sessions_read_bytes |  | long |
| gitlab_ce.production.redis_sessions_write_bytes |  | long |
| gitlab_ce.production.redis_write_bytes |  | long |
| gitlab_ce.production.remote_ip |  | keyword |
| gitlab_ce.production.request_urgency |  | keyword |
| gitlab_ce.production.target_duration_s |  | long |
| gitlab_ce.production.time |  | keyword |
| gitlab_ce.production.view_duration_s |  | long |
| gitlab_ce.production.worker_id |  | keyword |
| host.containerized | If the host is a container. | boolean |
| host.os.build | OS build information. | keyword |
| host.os.codename | OS codename, if any. | keyword |
| input.type | Type of Filebeat input. | keyword |
| log.file.device_id | ID of the device containing the filesystem where the file resides. | keyword |
| log.file.fingerprint | The sha256 fingerprint identity of the file when fingerprinting is enabled. | keyword |
| log.file.idxhi | The high-order part of a unique identifier that is associated with a file. (Windows-only) | keyword |
| log.file.idxlo | The low-order part of a unique identifier that is associated with a file. (Windows-only) | keyword |
| log.file.inode | Inode number of the log file. | keyword |
| log.file.vol | The serial number of the volume that contains a file. (Windows-only) | keyword |
| log.flags | Flags for the log file. | keyword |
| log.offset | Offset of the entry in the log file. | long |


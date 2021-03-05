---
layout: default
---
## LogBatchPurger class

Batch class used to delete old logs, based on Log__c.LogRetentionDate__c <= :System.today()

### Related

[LogBatchPurgeScheduler](log-management/LogBatchPurgeScheduler

---
### Methods
#### `execute(Database.BatchableContext batchableContext, List<Log__c> scope)` → `void`
#### `finish(Database.BatchableContext batchableContext)` → `void`
#### `start(Database.BatchableContext batchableContext)` → `Database.QueryLocator`
---
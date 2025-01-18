# TransactionStatus

Enum representing different transaction statuses.
These statuses indicate the current state of a billing transaction in the process pipeline.

## Enumeration Members

| Enumeration Member | Value | Description |
| ------ | ------ | ------ |
| <a id="completed"></a> `Completed` | `"Completed"` | Transaction has been successfully processed. |
| <a id="failed"></a> `Failed` | `"Failed"` | Transaction failed due to an error or rejection. |
| <a id="pending"></a> `Pending` | `"Pending"` | Transaction has been initiated but not yet processed. |

# intro

Webhook events

|event|activity|descr|
|-----|--------|-----|
|`workflow_job`|`queued`|A new job is ready for processing. The event includes label data, which should be used to identity the type of runner.|
|`workflow_job`|`completed`|Remove runner (i.e. unregister).|

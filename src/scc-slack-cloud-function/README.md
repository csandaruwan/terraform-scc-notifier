# terraform-scc-notifier
Terraform script for Google Cloud Security Command Center Enabling real-time Slack chat notifications

Use `scc.notifications.config.tf` alone with Terraform project. 

Create slack app with token and upload token in to Google Secret Manager.
- [How to quickly get and use a Slack API token](https://api.slack.com/tutorials/tracks/getting-a-token)


This Terraform script will create following GCP resources.
- google_pubsub_topic
- google_pubsub_subscription
- google_scc_notification_config
- google_storage_bucket
- google_storage_bucket_object
- google_service_account
- google_cloudfunctions_function


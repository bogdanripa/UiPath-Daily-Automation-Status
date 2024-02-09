# UiPath Daily Automation Status
Sends a daily email with the status of your automations, looking at queues and jobs that ran in the last 24 hours

The automation loops over all the folders defined in Orchestrator and, if there is action in their queues or jobs, includes this information in the email text.

It uses the Orchetsrator Monitoring APIs fo get the aggregated stats on each folder.

It is designed to run every 24 hours.

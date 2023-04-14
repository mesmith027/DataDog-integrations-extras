# Shipyard

## Overview

The Datadog Shipyard integration allows your Shipyard environemnt logs to be passed to Datadog and availabe in your datadog dashboard. This information is one way from your ephemeral (testing) environments to Datadog. Thsi is useful for using Datadog's [log analysis and correlation](https://www.datadoghq.com/solutions/log-analysis-and-correlation/) functions as well as helping your team with [shift left testing](https://www.datadoghq.com/solutions/shift-left-testing/). 

## Setup

This assumes you have a Shipyard account and dashboard set up. If you do not you can get started for [free here](https://shipyard.build/signup).

### Configuration

0. Go to your [Datadog APIs page][4] and create an API key.
1. In your Shipyard dashboard, go to settings. 
2. Under the Datadog section enter your Datadog API key and the Datadog site URL. 
   1. If you do not see a Datadog section here, email [support@shipyard.build](mailto:support@shipyard.build) to get this feature enabled for your organization.
![datadog-input][5]
3. Click the "install Datadog" button.
   1. Optionally, toggle the "enable Datadog logging for all environments" and Shipyard will automatically send the logs for all your environments. 
4. To select specific environments from which you want to send logs, visit the [Configure Application page](https://docs.shipyard.build/docs/config) for each repo you want the logs for. 
   1. Select the third tab "Notification Settings". 
   2. Toggle the "Enable Datadog logging" for this environment.

## Data Collected

### Metrics

Shipyard does not include any metrics.

### Service Checks

Shipyard does not include any service checks.

### Events

Shipyard does not include any events.

## Troubleshooting

Need help? Contact [Datadog support][3].

[1]: https://shipyard.build/
[2]: https://app.datadoghq.com/account/settings#agent
[3]: https://docs.datadoghq.com/help/
[4]: https://app.datadoghq.com/organization-settings/api-keys
[5]: https://raw.githubusercontent.com/mesmith027/DataDog-integrations-extras/shipyard-integration/shipyard/images/datadog-input.png
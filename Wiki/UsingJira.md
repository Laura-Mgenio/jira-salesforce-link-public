# Using Jira

## Adding Jira Account

#### 1. Login to Jira Project

1. Select Project Settings in sidebar and take note of the project Name Key and Host

[<img src="images/figure14.png" width="250"/>](images/figure14.png)

[<img src="images/figure15.png" width="250"/>](images/figure15.png)

[<img src="images/figure16.png" width="250"/>](images/figure16.png)

- Ex:
- Name: SalesforceTest,
- Key: SAL,
- Host: salesforcetest.atlassian.net

2. Create API token in Jira

- Open Link: [https://id.atlassian.com/manage-profile/security/api-tokens](https://id.atlassian.com/manage-profile/security/api-tokens)
- select Create and Name API token and save the token in a safe place

  [<img src="images/figure17.png" width="250"/>](images/figure17.png)

  [<img src="images/figure18.png" width="250"/>](images/figure18.png)

#### 2. Login Salesforce

1. Add Jira Project to Salesforce

- Search for Jira Projects Tab in App search and select it

[<img src="images/figure19.png" width="250"/>](images/figure19.png)

- Select new and add your Jira project

Ex:

- Name: SalesforceTest,
- Key: SAL,
- Host: salesforcetest.atlassian.net
- Email: Your Jira account email ie: user@email.com
- API Token: **\*\*\*\***\*\*\*\***\*\*\*\***

[<img src="images/figure20.png" width="450"/>](images/figure20.png)

- Click Save
- Now your jira account is linked.

## Creating Cases

#### 1. Go to Cases and Select new

- When creating a Case, be sure to select the Jira Project you wish the Case to go to

[<img src="images/figure21.png" width="450"/>](images/figure21.png)

- New case will be synced with Jira

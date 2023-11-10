# API Calls inside Qualtrics Surveys

## Useful Links

[Common API Use Cases - Qualtrics](https://www.qualtrics.com/support/integrations/api-integration/common-api-use-cases/)

[Qualtrics API Docs](https://api.qualtrics.com/)

## Find your Qualtrics IDs

Use this URL, once you are logged into Qualtrics, to find your IDs

https://unc.az1.qualtrics.com/Q/QualtricsIdsSection/IdsSection

We will need the following:

1. Datacenter ID
2. API token

## Exercise

1. Create a new Qualtrics survey.
2. Collect FirstName, LastName, Email in the survey.
3. Create a mailing list with nothing in it.
4. Look at the documentation for creating a contact via API: https://api.qualtrics.com/f13aeb845e7a0-create-contact
5. Identify the Survey ID and Mailing List ID that you need. 
6. Attempt to construct a curl call that will enter a new contact into your mailing list
7. Use the web service feature in Qualtrics to do the same thing.

---

[Return to main page](../../)

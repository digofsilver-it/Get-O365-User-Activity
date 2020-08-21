# Get Office365 users activity
Get users usage from O365 features

### Prerequisites

You needs to have implemented on your Azure portal a App Registration created to the script connect.
This App needs to have the permissions below:

```
Reports.Read.All - Application (Read all usage reports)
User.Read - Delegated (Sign in and read user profile)
```

## Running script

To run the script, you needs to complement the below variables

```
ClientID - Get this info on your App Registration
ClientSecret - Get this info on your App Registration
TenantName
GraphUrl (example on script)
```

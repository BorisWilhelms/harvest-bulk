# harvest-bulk

Script to create harvest time tracking entries in bulk.

## What you need

- Personal Access Token: Must be created in [Harvest Developer Tools](https://id.getharvest.com/developers).
- Account ID: Can be retrieved when you create the personal access token.
- Configure `PROJECT_ID` and `TASK_ID` in the script
- Configure `START_DATE` and `END_DATE`
  - The script will exclude weekends
  - `START_DATE` and `END_DATE` are inclusive

## How to run

Export the Personal Access Token and the Account ID and run the script.

```shell
export HARVEST_ACCESS_TOKEN=....
export HARVEST_ACCOUNT_ID=....

./harvest-bulk
```


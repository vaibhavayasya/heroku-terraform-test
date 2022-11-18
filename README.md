# Deploy, Manage, and Scale a NodeJS Application on Heroku

This is a companion repository to the ["Deploy, Manage, and Scale a NodeJS Application on Heroku" tutorial](https://developer.hashicorp.com/terraform/tutorials/applications/heroku-provider).

# Add the following environment variables before running the relevant commands

```
export HEROKU_API_KEY=<api_key_from_heroku>
export HEROKU_EMAIL==<heroku_account_email_id>
```

# After the environment variables run the following commands

```
terraform init 
```

- The following command will ask to write a yes
- Before typing yes validate the logs as to what all is terraform going to provision
```
terraform apply 
```


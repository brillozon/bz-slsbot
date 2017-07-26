# bz-slsbot

Simple Slack chatbot using serverless infrastructure on AWS.

This is taken from an aCloudGuru class onchatbots.

Expect changes.  :-)

# deploying the bot

```bash
bash> sls deploy -v
```

# deploying the website

```bash
bash> aws s3 sync --delete site/ s3://<site-bucket>/
```

Then use the site to install to a Slack team.

# configuring slack

   ...tdb...

# using the chatbot

In a channel:

```
@bz-slsbot convert <amount> <original currency> <target currency>
```


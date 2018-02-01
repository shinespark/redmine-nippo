# Redmine-Nippo
Post yesterday's redmine activity to Slack.

This scripts use `Slack Web API token` .  
Get Slack Web API token: [Legacy tokens | Slack](https://api.slack.com/custom-integrations/legacy-tokens)

# Usage

```
$ pip install -r ./requirements.txt
$ cp conf{_original,}.yml
$ vi conf.yml
# change to your settings.

$ crontab -e
# add <as you like time> python3 <abs_path>/redmine-nippo.py
```

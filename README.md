# Collect Logs before restarting Host.
If you have an issue, consider collecting your logs before restarting  your Host.
Once the Host is started, the previous logs are deleted.

- You can use this script to simplify your copy paste or screenshot effort.
- One thing this script does is shorten your wait on backing-up the logs twice and having an option for one copy to include timestamps.
- Lastly, it provides a command to display limited amount of text if the error just happend a few jobs ago.
- The sudo command is only included to cover the chance that you may not have rights to save in the logs directory

-# script command
```wget -qO- https://github.com/MachoDrone/HostLogs/raw/main/HostLogs.sh | bash```

RESULT:
![screenshot](zHostLog.png)

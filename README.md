# specify_auto_update
Automated Data update for Specify Web Portal

### Kick off watchdog monitor with watchmedo script:

```
$ watchmedo shell-command \
> --pattern "*-websearchdata.zip" \
> --recursive \
> --command='python automate.py' \
> 
```

automate.py can call out to different methods based on what the * value is

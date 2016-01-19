- Add a whitelist of Slack users that can start a build. Get the internal Slack users when starting.
- Use a better Logger for the output messages; don't need the redundant 'INFO - '
- Add the host and port to the .bbconfig
- Enable getting the log files from the server; either a link to the file (must be secured) or enable sending them via slack
- Clean-up log files older than some (configurable) number of days
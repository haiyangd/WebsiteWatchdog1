A website watchdog. Executing periodically via a cron.

The config_file_path is the path for a file where each row has the following structure:

domain;check1;check2...

each check is a string that must exist in the root document of the domain


Still a lot TODO:
* Run as a daemon instead of cron
* do not resend emails for repeated failures
* more complex tests (e.g. regex)
* machine-learning for automatic random website checks

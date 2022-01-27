# Periodic jobs on Fly.io with Supercronic

Evenutally, Fly.io will offer native periodic jobs. For now, it's simple to add this behavior to your app using the excellent
[Supercronic](https://github.com/aptible/supercronic) tool. It works like cron but designed for container-like environments
where only one process will be running, logging to stdout.

Check out the Dockerfile here and swipe the contents to try it out on your app. You'd probably want to deploy a separate app
on Fly to run these jobs in a single VM.

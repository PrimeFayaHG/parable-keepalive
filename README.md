# parable-keepalive

GitHub Actions pings https://parableadvisory.com/ so the free Render web service keeps receiving traffic.

Render sleeps a free web service after 15 minutes with no requests. The Render cron in the website repo never started, because a new service is only created when a Blueprint is synced. This repository is public so the scheduled runs use GitHub's free runners.

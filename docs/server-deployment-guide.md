# Server Deployment Guide

## 1. Check the server
- Use `whoami` to confirm the current user.
- Use `hostname` to identify the server.
- Use `df -h` to check disk space.
- Use `free -h` to check memory usage.
- Use `uptime` to check how long the server has been running.

## 2. Prepare for deployment
- Confirm that the correct Git branch is checked out.
- Review changes before committing.
- Ensure the application configuration is correct.

## 3. Verify the deployment
- Check application logs.
- Confirm that the required service is running.
- Test the application endpoint.

## 4. Recovery
- Review Git history before undoing commits.
- Keep important work committed and pushed.

# Linux Troubleshooting Guide

## 1. Check system identity
- Use `whoami` to identify the current user.
- Use `hostname` to identify the machine.

## 2. Check system resources
- Use `df -h` to check disk space.
- Use `free -h` to check memory.
- Use `uptime` to check system uptime.

## 3. Check network connectivity
- Use `ip addr` to inspect network interfaces.
- Use `ping` to test connectivity to a destination.
- Use `ss -tulpn` to inspect listening ports.

## 4. Troubleshooting process
- Identify the problem.
- Gather evidence before changing settings.
- Make one change at a time.
- Test the result and document the fix.

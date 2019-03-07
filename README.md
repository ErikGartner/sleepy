# Sleepy
*A Docker container that just sleeps*

## Usage

By default, Sleepy waits 60 seconds then exits. Use the `TIME` variable to pass
time to the `sleep` command.

Run using:
```bash
docker run -e TIME=5 erikgartner/sleepy:latest
```

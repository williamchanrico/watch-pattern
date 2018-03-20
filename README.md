# watch-pattern
Shell script to monitor a file (live) and trigger something on matched pattern

## Usage
Remember to modify the script's post-match part to do what you want
```
$ watch-pattern
usage: watch-pattern PATTERN LOG_FILE
```

## Example
```
$ watch-pattern "123.123.123.123" /var/log/in.log
```

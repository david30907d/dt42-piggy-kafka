# DT42 Piggy Kafka

This config is almost the same as 

but has a single line difference cause i'm afraid our edge-device would run out of disk.

```
# The minimum age of a log file to be eligible for deletion due to age
log.retention.hours=2
```

## Install

Git clone:
1. `git clone --recursive`
2. `git clone; git submodule update --init`

Update submodule:
1. `cd <submodule>`
2. `git pull`
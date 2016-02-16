# NTP daemon

## Usage

### Manual

```bash
# start ntpd
docker run -d --cap-add='SYS_TIME' --name ntpd seznam/ntpd
# stop ntpd
docker stop ntpd

```

### Atomic host

```bash
# start ntpd
atomic run seznam/ntpd
# stop ntpd
atomic stop seznam/ntpd
```

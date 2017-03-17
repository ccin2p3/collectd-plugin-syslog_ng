# collectd-plugin-syslog_ng
Collectd plugin for syslog-ng statistics

## Example config

```
<Plugin "exec">
      Exec "collectd:collectd" "/opt/collectd/bin/syslog_ng-exec"
</Plugin>
```

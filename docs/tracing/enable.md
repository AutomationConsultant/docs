To enable tracing edit the monitor configuration file -
/opt/spm/spm-monitor/conf/spm-monitor-config-${token}-${jvm}.properties:

``` properties
# enable tracing agent
SPM_MONITOR_TRACING_ENABLED=true
 
# capture only transaction that took longer than this many milliseconds
# default value is 50ms
# WARNING: setting this too low will increase the agent overhead
MIN_TRANSACTION_DURATION_RECORD_THRESHOLD=50
```

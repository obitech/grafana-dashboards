# Telegraf Internal Stats


Requires:

```conf
[[inputs.internal]]
  collect_memstats = true
```

Uses:

- Grafana Prometheus datasource
- Telgraf Prometheus output plugin
- Telegraf vSphere input plugin (optional)

Shows:

- General resource consumption overview
- vSphere input plugin metrics
- Agent metrics
- Gather metrics
- Write metrics
- GC metrics

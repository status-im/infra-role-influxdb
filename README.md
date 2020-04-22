# Description

This role configues an [InfluxDB](https://www.influxdata.com/products/influxdb-overview/) instance for collecting of benchmarking metrics.

# Configuration

THe basic settings are:
```yml
influxdb_cont_name: 'influxdb-abc'
influxdb_cont_port: 8086
influxdb_query_log: false
influxdb_admin_user: 'admin'
influxdb_admin_pass: '123qwe'
influxdb_databases:
  - name: service-a-metrics
    duration: 1w
  - name: service-b-metrics
    replicate: true
```

# Known Issues

__TODO__

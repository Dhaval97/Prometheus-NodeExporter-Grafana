# Prometheus-NodeExporter-Grafana
How to install Prometheus, Node Exporter and Grafana.

### Prometheus
* Prometheus is a free software application used for event monitoring and alerting. It records real-time metrics in a time series database (key-value format) built using a HTTP pull model, with flexible queries and real-time alerting.
* **Prometheus Metrics and it's Types**:
  * ***Counters***:
    * Record a value that only goes up
    * Query how fast the value is increasing
    * Eg: Number of requests served, task completed/errors
  * ***Gauges***:
    * Record a value that only goes up and down
    * You do not have to Query it's rate
    * Eg: Current memory usage, number of instances running
  * ***Histogram***:
    * Take many measurements of a value, to later calculate averages or percentiles

### Node Exporter
* Node Exporter is a Prometheus exporter for server level and OS level metrics with configurable metric collectors. It helps us in measuring various server resources such as RAM, disk space, and CPU utilization.

### Grafana
* Grafana is a multi-platform open source analytics and interactive visualization web application. It provides charts, graphs, and alerts for the web when connected to supported data sources.

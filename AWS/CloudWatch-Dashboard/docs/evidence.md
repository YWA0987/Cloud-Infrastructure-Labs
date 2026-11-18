# Screenshot evidence

These images document the **guided MGS402 CloudWatch dashboard exercise**. They show configuration and selected metrics, not production resource ownership or completed alarms.

| File | Evidence |
| --- | --- |
| [dashboard-overview.png](../screenshots/dashboard-overview.png) | Four configured widgets: memory, 404 errors, load-balancer traffic, and CPU |
| [webserver1-404-metric-filter.png](../screenshots/webserver1-404-metric-filter.png) | `404` filter pattern for first web server, `Lab` namespace, count value |
| [webserver2-404-metric-filter.png](../screenshots/webserver2-404-metric-filter.png) | Same filter pattern for second web server |
| [widget-type-selection.png](../screenshots/widget-type-selection.png) | Choosing a CloudWatch line graph widget |
| [memory-metrics-selection.png](../screenshots/memory-metrics-selection.png) | CloudWatch Agent memory metrics for both EC2 instances |
| [custom-404-metrics-selection.png](../screenshots/custom-404-metrics-selection.png) | Both custom 404 metrics in the `Lab` namespace |
| [load-balancer-metrics-selection.png](../screenshots/load-balancer-metrics-selection.png) | Application Load Balancer request count, processed bytes, and response time |
| [cpu-metrics-selection.png](../screenshots/cpu-metrics-selection.png) | CPU utilization metrics for both web servers |

### Verification boundaries

The uploaded screenshots show the named metrics selected and plotted in the dashboard. They do **not** show alert rule configuration, messages or notifications, or proof of an ongoing production monitoring setup. The HTTP 404 log generation was described by the student as part of the guided exercise.

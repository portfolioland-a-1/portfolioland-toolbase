---
tags:
alias:
date: 2022-10-14 @ 19:10
---

# [[Grafana]]


**Grafana** ist eine [plattformübergreifende](https://de.wikipedia.org/wiki/Plattform%C3%BCbergreifend "Plattformübergreifend") [Open-Source](https://de.wikipedia.org/wiki/Open_Source "Open Source")-Anwendung zur grafischen Darstellung von Daten aus verschiedenen Datenquellen wie z. B. [InfluxDB](https://de.wikipedia.org/wiki/InfluxDB "InfluxDB"), [MySQL](https://de.wikipedia.org/wiki/MySQL "MySQL"), [PostgreSQL](https://de.wikipedia.org/wiki/PostgreSQL "PostgreSQL"), [Prometheus](https://de.wikipedia.org/wiki/Prometheus_(Software) "Prometheus (Software)") und Graphite.

Die erfassten Rohdaten lassen sich anschließend in verschiedenen Anzeigeformen ausgeben. Diese können dann zu sogenannten [Dashboards](https://de.wikipedia.org/wiki/Dashboard_(Informationsmanagement) "Dashboard (Informationsmanagement)") zusammengefügt werden. Die Anzeigemöglichkeiten und Datenquellen können zudem mittels [Plug-ins](https://de.wikipedia.org/wiki/Plug-in "Plug-in") erweitert werden.

Beispiel für ein Grafana-Dashboard

Grafana wird häufig für [Überwachungsanwendungen](https://de.wikipedia.org/wiki/Monitoring "Monitoring") verwendet und unterstützt die drei Säulen der Observability: Metriken, [Logging](https://de.wikipedia.org/wiki/Logging "Logging") und [Tracing](https://de.wikipedia.org/wiki/Tracing "Tracing"), kann aber auch zur Darstellung von statischen Daten in [relationalen Datenbanken](https://de.wikipedia.org/wiki/Relationale_Datenbank "Relationale Datenbank") genutzt werden.
[![Grafana|center](https://github.com/grafana/grafana/raw/main/docs/logo-horizontal.png)](https://github.com/grafana/grafana/blob/main/docs/logo-horizontal.png)

The open-source platform for monitoring and observability 

Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored. Create, explore, and share dashboards with your team and foster a data-driven culture:

-   **Visualizations:** Fast and flexible client side graphs with a multitude of options. Panel plugins offer many different ways to visualize metrics and logs.
-   **Dynamic Dashboards:** Create dynamic & reusable dashboards with template variables that appear as dropdowns at the top of the dashboard.
-   **Explore Metrics:** Explore your data through ad-hoc queries and dynamic drilldown. Split view and compare different time ranges, queries and data sources side by side.
-   **Explore Logs:** Experience the magic of switching from metrics to logs with preserved label filters. Quickly search through all your logs or streaming them live.
-   **Alerting:** Visually define alert rules for your most important metrics. Grafana will continuously evaluate and send notifications to systems like Slack, PagerDuty, VictorOps, OpsGenie.
-   **Mixed Data Sources:** Mix different data sources in the same graph! You can specify a data source on a per-query basis. This works for even custom datasources.
## Supported databases[](https://grafana.com/docs/grafana/v9.0/setup-grafana/installation/#supported-databases)

Grafana requires a database to store its configuration data, such as users, data sources, and dashboards. The exact requirements depend on the size of the Grafana installation and features used.

Grafana supports the following databases:

-   [[SQLite]]
-   [[MySQL]]
-   [[PostgreSQL]]
- [[Prometheus]]
- [[Graphite]]

https://grafana.com/ 

<iframe style="width: 100%; height: 1000px; overflow: hidden; background: #FFFF"  src="https://grafana.com/ " width="100" height="100" scrolling="no">Iframes not supported</iframe>

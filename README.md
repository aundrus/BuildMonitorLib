## build-monitor-lib

A drop-in **Django build monitoring module** (views, URL routes, utilities, and HTML templates) used
to power **ATLAS/BigPanDA** build dashboards for **CI** and **nightly** pipelines, designed to fit
into **jQuery/DataTables-style** front-end pages.

It renders both **HTML pages** and **JSON endpoints** for:
- Global build status overview
- CI builds summary
- Nightly builds summary
- Test results and component/package results drill-downs

The module queries build/test status from **Oracle-backed tables** (via Django DB cursors)
and enriches dashboards with **cached test results**,
plus UI status indicators (OK/warn/error/updating) for interactive, sortable tables.

Developed for integration with
**[PanDAWMS/panda-bigmon-core](https://github.com/PanDAWMS/panda-bigmon-core)**.




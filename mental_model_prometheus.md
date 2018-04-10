# Mental Model

A mental model to help people not familiar with it (or a certain aspect) to navigate the prometheus world

## Life of a metric

User-centric overview of what happens with a countable event from instrumentation to deleting after the end of retention date.

1. Event
1. Instrumentation (potential excursus to exporters)
1. Incrementation (potential excursus to different metric types)
1. Scraping
1. Service Discovery
1. Relabeling before scraping
1. Relabeling before ingestion
1. Saving
1. Qerying
1. Deletion

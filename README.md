# Data Engineering Portfolio

Welcome to my first Data Engineering portfolio project!

# Projects

### subscriber-pipeline

A semi-automated bash+python pipeline to regularly transform a messy SQLite database into a clean source of truth for an analytics team. The pipeline
- performs unit tests to confirm data validity
- writes human-readable errors to an error log
- automatically checks and updates changelogs
- updates a production database with new clean data

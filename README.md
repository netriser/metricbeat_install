# Metricbeat and Filebeat Install Role

An Ansible role to install and configure Metricbeat/Filebeat, a lightweight shipper for metrics and logs.

## Features
- Installs Metricbeat/Filebeat on Debian, ubuntu
- Configures Metricbeat/Filebeat to collect metrics from system and services.
- Manages Metricbeat/Filebeat service for startup and runtime configuration.

## Requirements
- Ansible 2.9 or higher.
- Supported platforms:
  - **Debian-based systems:** Ubuntu, Debian.
- Elasticsearch or Logstash must be available as a data sink.

## Role Variables
The following variables can be customized for this role:

### Defaults
Located in `defaults/main.yml`:
```yaml
# Default Metricbeat modules to enable
metricbeat_modules: []
filebeat_modules: []
```
## Dependencies
None.

## License
MIT

## Author Information
This role was created by Chakib. Contributions and feedback are welcome!


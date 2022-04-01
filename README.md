# blackbox_exporter
Prometheus: Blackbox Exporter

| Variable            | Default                                                                                                                                                 | Description                                               |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|
| `blackbox_version`  | `0.19.0`                                                                                                                                                | Version that will be installed                            |
| `blackbox_url`      | `https://github.com/prometheus/blackbox_exporter/releases/download/v{{ blackbox_version }}/blackbox_exporter-{{ blackbox_version }}.linux-amd64.tar.gz` | URL from which blackbox exporter will be downloaded       |
| `blackbox_checksum` | `sha256: af2ae1394c4f9b46962ac1510e1dacac78115c11e625991fb6c54825d2240896`                                                                              | Checksum can be found on Github releases                  |
| `blackbox_dir`      | `/opt/blackbox_exporter`                                                                                                                                | Directory in which blackbox exporter will be installed to |
| `blackbox_user`     | `blackbox_exporter`                                                                                                                                     | User that will run blackbox exporter                      |

# Helm Chart for Libvirt Exporter

## Description


## Configuration

The chart configuration is done in the `values.yaml` file.

## Usage

```bash
# Get a local copy
git clone https://github.com/saeed-mcu/libvirt-exporter-helm-charts.git

# Package the chart
cd charts/
helm package .

# Get chart version & install
version="$(awk '/^version:/{ print $NF }' Chart.yaml)"
helm install prometheus-libvirt-openstack-exporter prometheus-libvirt-exporter-${version}.tgz
```

## Contributing

Please fill pull requests or issues under Github.

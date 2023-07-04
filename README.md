# Monitor dashboards

Monitor dashboards used by [monitor service](https://github.com/dappnode/monitor-service) and [monitor aggregator](https://github.com/dappnode/monitor-aggregator). These dashboards aims to collect all the dashboards required to visualize and annalize data emitted by dappnodes. It must be developed taking into account performance, as long as the amount of data collected is huge.

## Releasing

After adding/editing dashboards, a new release must be created manually (through `workflow_dispatch`). There must be given the input of the release version (prefixed by `v`, i.e `v0.1.0`). Then, the monitor proxy and monitor aggregator must be re-compiled with the new monitor dashboards version in orde to have the new dashboards.

## Contributing

Please refer to the [Contributing Guide](CONTRIBUTING.md) for details on how to contribute to this project.

## Issues

Report issues in the [Issues section](https://github.com/dappnode/monitor-service/issues) of the GitHub repository.

## License

Monitor-Service is released under the [MIT License](LICENSE).
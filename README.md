# Kubernetes cluster monitoring

Setting Up `STATELESS` Grafana and Prometheus in a Kubernetes Cluster

## Description

This project aims to provide an easy way to set up Grafana and Prometheus in a Kubernetes cluster. It utilizes taskfile.dev, a task runner tool, to simplify the setup process.

## Installation

To install and set up Grafana and Prometheus in your Kubernetes cluster, follow these steps:

1. Clone the repository to your local machine.
2. Install `task` from [taskfile.dev](https://taskfile.dev/installation/) by following the instructions in their official documentation.
3. Make sure you have configured `kubectl`.
4. Run `task init` to initialize the setup process.
5. Once the setup is complete, you can access Grafana (default login/password is `admin`/`admin`) and Prometheus dashboards to monitor your Kubernetes cluster.

## Usage

To use the installed Grafana and Prometheus in your Kubernetes cluster, you can run the following tasks using taskfile:

- `task init`: Initializes the setup process.
- `task destroy`: Tears down the Grafana and Prometheus installation in your Kubernetes cluster.

## Contributing

If you would like to contribute to this project, you can do so by submitting pull requests or reporting issues on the repository.

## License

This project is released under the MIT License. Please review the LICENSE file for more information.

## Contact Information

For any questions or inquiries about this project, you can contact the project owner at fmpanic@gmail.com

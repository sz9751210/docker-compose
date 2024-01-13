# docker-compose

## Introduction

This project provides a Docker Compose setup designed for DevOps and Site Reliability Engineering (SRE) teams. It focuses on creating a service environment that can be quickly deployed and scaled according to the needs of the organization.

## Features

- Rapid deployment of service environments.
- Easy scalability and configuration.

## Prerequisites

- Docker and Docker Compose installed on your machine.
  Can use the [script](https://github.com/sz9751210/useful-script/blob/main/linux/install_docker.sh)

## Installation and Setup

1. Clone the repository: `git clone https://github.com/sz9751210/docker-compose.git`.
2. Navigate to the project directory: `cd docker-compose`.
3. Choose the service you want to use. For example, to use Apache, navigate to the Apache directory: `cd apache`.
4. Run Docker Compose for the selected service: `docker-compose up`.

## Usage

### Linux distro

| Name   | Version |
| ------ | ------- |
| Ubuntu | 22.04   |
| CentOS | 7       |
| Alpine | 3.19    |

### webservice

| Name   | Version |
| ------ | ------- |
| Nginx  | 3.18    |
| Apache | 3.19    |

### Database

| Name       | Version |
| ---------- | ------- |
| MySQL      | 5.7     |
| MongoDB    | 7.0.5   |
| ClickHouse | 23.8    |
| Redis      | 6       |

### CICD

| Name    | Version |
| ------- | ------- |
| Jenkins |         |
| GitLab  |         |
| Gitea   | 1.13.3  |

### Monitor

| Name       | Version |
| ---------- | ------- |
| Prometheus | 2.48.1  |
| Grafana    | 8.4.4   |
| Cadvisor   | 0.33.0  |

## Configuration

[Details on any configuration steps or customization of the Docker Compose files.]

## Contributing

Contributions are welcome! Please read our contributing guidelines for more information.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact/Support

E-mail: alandev9751210@gmail.com

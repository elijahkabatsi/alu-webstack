# Load Balancer

## Description
This project configures a load balancer setup with two web servers (web-01 and web-02) behind an HAProxy load balancer (lb-01). It adds redundancy and improves reliability of the web infrastructure.

## Servers
| Name | IP |
|---|---|
| web-01 | 3.89.31.111 |
| web-02 | 44.202.5.108 |
| lb-01 | 3.91.57.45 |

## Tasks
- **0-custom_http_response_header**: Configures Nginx with a custom X-Served-By header on web-01 and web-02
- **1-install_load_balancer**: Installs and configures HAProxy on lb-01 with roundrobin load balancing

## Usage
```bash
./0-custom_http_response_header
./1-install_load_balancer
```

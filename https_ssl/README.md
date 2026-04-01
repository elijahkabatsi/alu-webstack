# HTTPS SSL

## Description
This project covers HTTPS SSL configuration including SSL termination with HAProxy and redirecting HTTP traffic to HTTPS.

## Tasks
- **0-world_wide_web**: Bash script that displays DNS information for subdomains
- **1-haproxy_ssl_termination**: HAProxy configuration for SSL termination on port 443
- **2-redirect_http_to_https**: HAProxy configuration to redirect HTTP to HTTPS with 301

## Requirements
- HAProxy 1.5 or higher
- SSL certificate from certbot
- Domain configured with proper DNS subdomains

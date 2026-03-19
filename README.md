# HTTPS SSL

## Description
This project covers the concepts of HTTPS, SSL termination, and securing website traffic using HAProxy as a load balancer.

## Learning Objectives
- What are the 2 main roles of HTTPS SSL
- What is the purpose of encrypting traffic
- What SSL termination means

## Tasks

### 0. World Wide Web
A Bash script that displays information about subdomains of a domain.
- Usage: `./0-world_wide_web domain [subdomain]`

### 1. HAProxy SSL Termination
HAProxy configured to accept encrypted HTTPS traffic on port 443 using a Let's Encrypt certificate.

### 2. No Loophole in Website Traffic
HAProxy configured to automatically redirect all HTTP traffic to HTTPS with a 301 redirect.

## Requirements
- Ubuntu 16.04 LTS
- HAProxy 1.5 or higher
- Certbot for SSL certificate generation

# Proxy configuration guide
Setting the proxy on a Linux installation is primarily done via setting environment variables. There are three variables available – for HTTP traffic, HTTPS traffic, and by-pass traffic.

### HTTP_PROXY
Sets an endpoint for all HTTP traffic traversing port 80.
### HTTPS_PROXY
Similar to HTTP_PROXY, this sets an endpoint for all traffic SSL\TLS encrypted traffic traversing port 443.
### NO_PROXY
A comma-delimited list of subnets, IP addresses, hostnames, and domain names to exclude from the proxy. Traffic matching any of the patterns set here will go directly to the destination host.

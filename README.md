# Website-Infrastructure-Manager
A tool to simplify tasks like adding new servers to my config, restarting servers, or modifying load balancer parameters.

Current functions:
- Restart load balancer (v1 won't have 0 downtime)
- View load balancer config
- View load balancer logs
  - tail -n [regex]
  - cat [regex]
- View status of web servers (by port number)
  - Individual server
- View status of load balancer

Planned functions:
- Restart a server running on a specific port
- Add a new server to load balancer config
- Remove a server from load balancer config
- View status of web servers (by port number)
  - All servers
- View web server logs
  - \<port\> tail -n [regex]
  - \<port\> cat [regex]

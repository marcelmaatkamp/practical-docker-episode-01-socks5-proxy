# practical-docker.com
This is the source repository for episode 01 of https://www.practical-docker.com

In these talks I will give practical tips and tricks on how to effectively use Docker as a valuable tool to solve various problems or just use it for fun projects with all kinds of hardware and software! See my YouTube Channel with all episodes for more information.

* [YouTube Channel with all episodes](https://www.youtube.com/channel/UCxp65f-xyu4z1PvmZBKqZGQ)

# episode 01: socks5-proxy vs. port forwarding

Opening and forwarding specific ports per docker container is ok for a few containers, the more ports you open the more it becomes a hasstle and totally not clear which ports map to which container. 

A simple but very effective solution is to use a socks5 proxy. In this episode I will show how to install and use a socks5 proxy and what benefits it brings to use this solution which is that each container can be reached by its internal hostname which is the name of the container.

Docker containers used:
 * [serjs/go-socks5-proxy](https://hub.docker.com/r/serjs/go-socks5-proxy)
 
# Installation

# About
In these talks I will give practical tips and tricks on how to effectively use Docker as a valuable tool to solve various problems or just use it for fun projects with all kinds of hardware and software! See my [YouTube Channel with all episodes](https://www.youtube.com/channel/UCxp65f-xyu4z1PvmZBKqZGQ) for more information.
* [YouTube Channel with all episodes](https://www.youtube.com/channel/UCxp65f-xyu4z1PvmZBKqZGQ)

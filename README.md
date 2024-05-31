# My Homelab

This is a blurred version of my homelab (which is hosted in my own git server) but this could give you some starting point to set up yours. Let's begin.

# The infrastructure

Let's start with the servers. The container engine is Docker and the orchestrator is Docker Swarm

## Storinator

This is my storage server. All the heavy stuff goes here, including the arrTools and Navidrome. I am still migrating my Immich compose file to support docker swarm.

## LadyDiana

This is a old APU2 board which serves me as a DNS server (pihole) and it hosts my traefik istance, which helps me manage all of my domains.

## Network:

The main network is **BeeNetwork**, which is the overlay network which connects all of my nodes containers.
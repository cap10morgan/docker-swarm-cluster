# docker-swarm-cluster

This is a set of Bash scripts for provisioning Docker Swarm clusters with Consul and RabbitMQ.

Consul (or something like it) is a requirement for robust Docker Swarm clusters, so it's not really optional.

RabbitMQ is optional, though.

## Usage

Edit the `settings` file.

To provision a "staging" environment cluster:
`./provision-cluster staging`

Or you can run the individual scripts if you just want parts of what `provision-cluster` does.

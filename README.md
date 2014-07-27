This heat template aims to deploy a Docker container onto a CoreOS cluster.

Just an experiment.

To deploy:

heat stack-create -f heat-stable.yaml -P key-name=<ssh_keypair_name> \
-P discovery_key=<discovery_key> <desired_stack_name>

Discovery keys can generated at https://discovery.etcd.io/new

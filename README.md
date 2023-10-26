# Load Master Node POD CIDR reader

In order for the kemp load master to work correctly with Kubernetes it appears that I will need to connect my pod CIDR with each node and feed that information to Kemp Load master. 

As this doesn't happen automatically it causes a number of issues. 

This will serve only as a proof of concept and not to be used as a real worl example

# Steps ? Plans?

Create a pod with cilium


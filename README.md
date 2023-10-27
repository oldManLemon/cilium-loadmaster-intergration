# Load Master Node POD CIDR reader

In order for the kemp load master to work correctly with Kubernetes it appears that I will need to connect my pod CIDR with each node and feed that information to Kemp Load master. 

As this doesn't happen automatically it causes a number of issues. 

This will serve only as a proof of concept and not to be used as a real worl example

# Steps ? Plans?

So far I have a cron job that has two containers a bitnami/kubectl and a curlimages/curl container. From there I am pushing the changes up to the loadbalancer. 

I don;t know if it would be better to instead have it running as pod that is also watching for an event and then push the changes on an event. 

It is fairly simplestic at teh moment, it doesn't delete or anything. It is a bare bones curl call. 


I also need to move the api key and loadmaster address into a secret file.


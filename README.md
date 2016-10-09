# heat-templates
OpenStack Heat templates from my day to day job.
- `stack-2vms-1net-1router.yaml` - Deploys two instances, a new private network and configure connectivity, including a router and a floating IP address for one of the instances.
- `stack-2vms-exisiting-net.yaml` - Start two instances and connect them to an existing private network.
- `stack-2vm-anti-affinity.yaml` - Deploys two instances, network and router, creates a Sever Group and apply anti-affinity policy for the instances.

# ansible-collect-_data-iperf
This ansible playbook will do the next tasks:
Check connectivity between all duros_nodes in the cluster
Check for persistent memory in all targets, in case the persistent memory is = true - all.yml , and print output.
Check for active available RAM memory in cluster nodes   Sum and print the NVME devices in each node
Check connectivity to LB-repo from each node.
Perform iperf Network Test between a server and a client. (only one node for group), and generate a report, and also will print average bandwidth performance to the screen.

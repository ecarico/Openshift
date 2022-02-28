# Openshift
Connect the repository to vss code 
Update any environment specific information. 
Ssh in and get started.

	1. install-config.yml - (This will deploy the cluster)
	2. Ldap.yaml - (Configures Ldap)
	3. Groupsync.yaml - (Enables authentication based on Ad group member ship. Install the Group Sync Operator first from the Operators Hub)
	4. Clusterscaler.yml - (defines resource limits available to the cluster)
	5. Machineautoscaler.yaml - (enables autoscaling for a machine set)
	6. Infraset.yml - (Creates a separate machine set for infra resources)
	7. Infra.mcp.yaml - (creates machine config pool for the new infra machine set)
	8. Infra.mc.yaml - (creates separate machine config for the new machine set)
  9. Openshift4-backup.yaml - (configures a cron job for openshift backup)

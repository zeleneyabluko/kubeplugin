# kubeplugin

Below is a Kubernetes plugin for displaying resource usage for nodes/pods within a specific namespace.

To use the plugin, do the following:
1. Rename the kubeplugin file according to your desired name of the kubectl command (e.g., if you want it to be accessible with *kubectl foo*, you have to rename the file to 'kubectl-foo')
2. Move the file somewhere in your *$PATH*
3. Run the command in the format:
   kubectl [command_name] [resource_type] [namespace]
where:

*command_name* is a name defined on step 1,
*resource type* is either pods, or nodes
*namespace* is a selected namespace

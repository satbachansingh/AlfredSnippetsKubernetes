## Alfredsnippets to create k8s shortcuts(For MAC users only)

# Prerequisites:
 Alfred 4 must be installed with Powerpack enabled. Snippet functionality only gets enabled with powerpack. Free Version doesn't support that

# How to Import:

Download the file on you mac and double click it. The below popup will be seen. Click on Import

![alt text](https://github.com/satbachansingh/K8sAlfredSnippets/blob/main/images/Import.png)

After successful import there will be a new collection available with name "kubectl commands"
![alt text](https://github.com/satbachansingh/K8sAlfredSnippets/blob/main/images/AfterImport.png)
Please enable all the commands for the usage. Also make sure to enable "Automatically expand snippets by keyword" to enable the feature


# Command Details 

The shortcuts of the commands are written to with following standard 

<pre>
|-------------------|---------|
| Operation         | Shortcut|
|-------------------|---------|
| kubectl get       |    kg   |
|-------------------|---------|
| kubectl delete    |    kl   | 
|-------------------|---------|
| kubectl describe  |    kd   | 
|-------------------|---------|
| kubectl edit      |    ke   | 
|-------------------|---------|
| kubectl config    |    kc   | 
|-------------------|---------|
</pre>

<pre>
|-------------------|---------|
| Resource          | Shortcut|
|-------------------|---------|
| config map        |    cm   |
|-------------------|---------|
| serviceaccount    |    a    | 
|-------------------|---------|
| pod               |    p    | 
|-------------------|---------|
| replicaset        |    r    | 
|-------------------|---------|
| deployment        |    d    | 
|-------------------|---------|
| service           |    s    | 
|-------------------|---------|

</pre>

e.g to run "kubectl get pod" the shortcut is "kgp"

## Type commands on any terminal or editor for auto-expand 

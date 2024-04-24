# utilities


## [Custom Fetch Api for Typescript](./Fetch.ts)


### command to print private IP in macos
`echo "Private IP address:" $(ifconfig $(route -n get default | awk '/interface: / {print $2}') | awk '/inet / {print $2}')`

This is a public collection of artifacts I commonly use in DevTest labs. It will change over time as I test out new versions of Docker and other packages.

## Recommended Reading

- [Add a VM with artifacts to a lab in Azure DevTest Labs](https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-add-vm-with-artifacts)
- [Create custom artifacts for your DevTest Labs VM](https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-artifact-author)

## Related Resources

- [azure-devtestlab/artifacts](https://github.com/Azure/azure-devtestlab/tree/master/Artifacts)

## Artifacts in this repo

### Windows-Docker-v13-rc
This runs a PowerShell script from [@StefanScherer's repo](https://github.com/StefanScherer/docker-windows-box/blob/master/swarm-mode/scripts/update-docker-rc.ps1) to upgrade the installed Docker Engine to the latest v1.13-rc build. This is based off the open source Docker, not the commercially supported version.


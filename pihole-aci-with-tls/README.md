# A Pi-hole ARM Template for use in Azure Container Instances

- Creates a new or uses an existing Resource Group
- Creates a storage account, with 3 volumes: 2 volumes for the Pi-hole, and 1 for the nginx configuration.
- Creates a container group, with one container for the Pi-hole, and one for the nginx sidecar
- Contains a pre-created and preloaded SSL key and certificate within the nginx container. NOTE: once deployed, you should replace this key and certificate with your own for safety reasons.

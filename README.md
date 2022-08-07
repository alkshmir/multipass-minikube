# multipass-minikube
make a virtual machine where minikube is installed using multipass

## make a VM
- `ssh-keygen` and paste your public key to `ssh_authorized_keys` on `cloud-config.yaml`
- `./start.sh`
- `multipass list` and confirm the IP address of your VM
- `ssh -i YOUR_SECRET_KEY ubuntu@IP_ADDRESS` or `multipass shell ubuntu1`


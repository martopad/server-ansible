Automating the services/configurations I do on my homelab.

Current use-cases:
1. Provision bcachefs storage pools.
2. Provision nfs servers.
3. Provision samba servers.

How to use:
```
ansible-playbook --inventory inventories/homelab.yaml  --private-key <YOUR_KEY> main.yaml
```

Notes:
- My server uses Gentoo Linux Distribution.
- This repo assumes that the user already provisioned the target machines to have proper permissions. Permisisons like ssh auth, root access, and etc.

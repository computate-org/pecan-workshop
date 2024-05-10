## Initialize the vault

```bash
env \
  REDHAT_OPENSHIFT_HOST=https://api.crc.testing:6443 \
  REDHAT_OPENSHIFT_TOKEN=... \
  env VAULT_UNSEAL_KEY=... \
  VAULT_ROOT_TOKEN=... \
  ansible-playbook ansible/vault-configure.yml
```


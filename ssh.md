# SSH
-----

## File permissions

| File            | Permissions | Command                            |
|-----------------|-------------|------------------------------------|
| Folder          | 700         | `chmod 700 ~/.ssh`                 |
| Authorized keys | 644         | `chmod 644 ~/.ssh/authorized_keys` |
| Known hosts     | 644         | `chmod 644 ~/.ssh/known_hosts`     |
| Config          | 644         | `chmod 644 ~/.ssh/config`          |
| Private keys    | 600         | `chmod 600 ~/.ssh/id_rsa_*`        |
| Public keys     | 644         | `chmod 644 ~/.ssh/*.pub`           |

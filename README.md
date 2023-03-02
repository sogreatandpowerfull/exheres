# About
Highly experimental personal exheres (paludis) for Exherbo Linux.

## Using This Repository
Edit `/etc/paludis/repositories/sogreatandpowerful.conf` and include the following:
```conf
format = e
location = /var/db/paludis/repositories/sogreatandpowerful
sync = git+https://github.com/sogreatandpowerful/exheres.git
sync_options = --branch=experimental
```
Then execute `cave sync sogreatandpowerful` to sync and update the repository.

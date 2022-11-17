
### Configuration
By default, only user selected at installation can read from and write to topics. To change this refer to the upstream project's documentation: https://docs.ntfy.sh/config/#access-control

The configuration file is located at `/var/www/<app>/server.yml`.

### Limitations
- requires a dedicated (sub-)domain#
- no LDAP support by upstream application

### Known Issues
- Yunohost's SSO injects the header `email` to every http request (if you are logged in). ntfy interprets this header to send an email notification, which leads to an error if email notifications are disabled/not configured.

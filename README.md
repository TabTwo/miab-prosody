Prosody module for mail in a box

Architecture of Mail in a box
https://mailinabox.email/static/architecture.svg

MIAB API
https://mailinabox.email/api-docs.html

- [ ] mod_auth_imap https://modules.prosody.im/mod_auth_imap.html
- [ ] pull all domains from miab
- [ ] create a config file for each domain -> ansible/jinja2?
- [ ] make miab adminuser admin in each domain or create user and send mail to admin
- [ ] how to get a list of miab admins?
- [ ] create dns entries
- [ ] create tlsa records
- [ ] pull in certificates from miab, certbot hook available?
- [ ] do users have to be created manually or are they created on the fly by auth_imap?
- [ ] web chat like /mail -> /xmpp, how to integrate in nginx?
https://modules.prosody.im/mod_conversejs.html
- [ ] what modules?
- [ ] recognize new domains, preferably by hook
- [ ] muc for every domain

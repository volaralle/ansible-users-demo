# Sketch ansible role for global user management
Files:
- **hosts** - group file with hosts for the connection, complete the group split, now works at the all level (all hosts)
- **play.yml** - main file for running
- **keys-alias.yml** - file for adding pub keys at the variable level in the format user_pub_name: [{key: pub key, subject to verification}]
- **user-list.yml** - individual file with user management, via + add pub aliases as variables, deleted - true\false deletion accordingly


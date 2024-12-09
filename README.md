# Amavis-Digest
## about the project
**and why it is not started as a fork**
- it is focusing on generate e-mail digests from the database of amavisd-new quarantine
- depend only on [amavis](https://gitlab.com/amavis/amavis) (perl) and PHP, so it will be no plugin of SquirrelMail
- aims compatibility with PHP version 7.4 (historical goal)
- aims compatibility with PHP version 8.x
- optionally work together with a MailZu installation by directing the user to MailZu login
- ... (what the future holds?)

## the main branch is always WIP
The first steps, initial TODO:
- [ ] try to extract the relevant parts that generate quarantine-digest
- [ ] use rectorphp/rector to upgrade the code to 7.4
- [ ] examine options to move to manage the PHP part with composer
- [ ] use rectorphp/rector to upgrade the code to 8.x

##### based on [jimmydigital/amavisnewsql](https://github.com/jimmydigital/amavisnewsql)

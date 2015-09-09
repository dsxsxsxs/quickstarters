# GitLab

[Docker GitLab](https://hub.docker.com/r/sameersbn/gitlab/) for [sloppy.io](http://sloppy.io).

## Start it

```
sloppy start gitlab.json  -var=USERNAME:my-username,URI:mydomain.sloppy.zone,DB_USER:my-db-user,DB_PASS:my-db-pass,DB_NAME:my-db-name

Example:

sloppy start gitlab.json  -var=USERNAME:john,URI:mygitlab.sloppy.zone,DB_USER:gitlab,DB_PASS:password,DB_NAME:gitlabhq_production
```

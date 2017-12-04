openntp
=======


What is does this role do?
--------------------------

This role installs and configures openntp.  Default servers are provided.

Meta
----

Files Managed:
  * /etc/sv/ntpd
  * /var/service/ntpd

Defaults Provided:
  * ntp_servers:
    * 0.pool.ntp.org
    * 1.pool.ntp.org
    * 2.pool.ntp.org
    * 3.pool.ntp.org

Variables Required:
  * None

Optional Variables:
  * ntp_servers: list of server addresses to ask for time

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * Network

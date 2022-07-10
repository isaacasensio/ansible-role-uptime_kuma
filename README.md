uptime_kuma
=========

Installs [Uptime Kuma](https://github.com/louislam/uptime-kuma) as a docker container


Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

```
kuma_image: "louislam/uptime-kuma:1.16.1-alpine"
```
The version of the kuma image to run as a container.

```
kuma_host_port: 3001
```
Host exposed port from where to reach Kuma.

```
kuma_host_data_path: /etc/uptime-kuma
```
Host path which will contain Kuma configuration.

```
kuma_container_user: pi
```
User who will run the container.


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - iasensio.uptime_kuma

License
-------

MIT


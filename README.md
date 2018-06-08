# ansible-offline-yum-repo

An [Ansible](https://www.ansible.com) role to configure locally internal Yum Repos.

## Requirements

You must configure your clients to use this hosted offline repo(use example below):

`/etc/yum.repos.d/offline-yum.repo`:

```bash
[OfflineYUM]
name=Local YUM
baseurl=http://192.168.1.100/CentOS/7
gpgcheck=0
enabled=1
```

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Example Playbook

## License

MIT

## Author Information

Larry Smith Jr.

-   [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
-   [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
-   <mailto:mrlesmithjr@gmail.com>

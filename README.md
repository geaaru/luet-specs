# luet-specs
Geaaru Luet Specs Repository

# Configure repository

To consume this repository with Luet, just create this file as `/etc/luet/repos.conf.d/geaaru.yaml`:

```yaml
name: "geaaru"
description: "Geaaru Repository"
type: "http"
enable: true
cached: true
priority: 1
urls:
  - "https://geaaru.keybase.pub/luet-repo"
```

or just run this command:

```shell
$> wget -O /etc/luet/repos.conf.d/geaaru.yaml https://raw.githubusercontent.com/geaaru/luet-specs/master/contrib/geaaru.yml
```

Pushing things in keybase sometimes stalled. I will do less upgrade and i will check the repository `stable`:

```shell
$> wget -O /etc/luet/repos.conf.d/geaaru-stable.yaml https://raw.githubusercontent.com/geaaru/luet-specs/master/contrib/geaaru-stable.yml
```

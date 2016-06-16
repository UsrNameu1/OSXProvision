# Prerequisites

## Xcode

```
$ sudo xcodebuild -license
```

## Homebrew

```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## Ansible

```
$ brew update
$ brew install ansible
```

## Git

```
$ brew install git
```

# Execute playbook

```
$ ansible-playbook -i hosts -vv main.yml
```



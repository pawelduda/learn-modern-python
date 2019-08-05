# Getting started

## Install Python
- [ ] Install asdf for managing Python (and other) versions

- [ ] Install Python plugin via asdf
```
$ asdf plugin-add python
```

- [ ] Install Python prerequisites (optional, in case of errors)
```
https://stackoverflow.com/questions/27022373/python3-importerror-no-module-named-ctypes-when-using-value-from-module-mul#41310760

$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get dist-upgrade
$ sudo apt-get install build-essential python-dev python-setuptools python-pip python-smbus
$ sudo apt-get install libncursesw5-dev libgdbm-dev libc6-dev
$ sudo apt-get install zlib1g-dev libsqlite3-dev tk-dev
$ sudo apt-get install libssl-dev openssl
$ sudo apt-get install libffi-dev
```

- [ ] Install Python via asdf
```
$ asdf install python 3.7.4
```

- [ ] Set installed Python as global default
```
$ asdf global python 3.7.4
```

- [ ] Try out installation (run interactive console)
```
$ python
```

## Next steps:
- [ ] Go through [Automate the Boring Stuff tutorial](https://automatetheboringstuff.com)

Total beginner level, I like it very much after a few chapters. It assumes no prior programming knowledge, so the first
chapters are very simple to go through.

- [ ] Go through [CS50’s Web Programming with Python and JavaScript](https://cs50.harvard.edu/web/2019/spring/lectures/)

No opinion yet

- [ ] Go through [Learn Code the Hard Way](https://learncodethehardway.org/python/)

No opinion yet


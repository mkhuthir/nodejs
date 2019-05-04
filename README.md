# Node.JS

### To insall Node.JS & npm

```bash
sudo apt update
sudo apt install nodejs npm
```
to check the version use the following:

```bash
nodejs --version
npm --version
```

to install from node source use the following

```bash
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
```


### How to update npm

```bash
sudo npm install -g npm
```
Occasionally, the version of npm will progress such that the current version cannot be properly installed with the version that you have installed already. (Consider, if there is ever a bug in the update command.) In those cases, you can do this:

```bash
curl https://www.npmjs.com/install.sh | sh
```
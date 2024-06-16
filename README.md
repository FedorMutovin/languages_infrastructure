# Learning Languages Infrastructure

## Setup
### Mac OS
- Install NVM and Node
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
nvm install node
```

- Install packages
```
npm install
```

- Install AWS CDK

```
npm install -g aws-cdk
```

- Install AWS CLI
```
curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
sudo installer -pkg AWSCLIV2.pkg -target /
```

- Configure credentials
```
aws configure
```

- Setup region for .aws/config
```
cat ~/.aws/config

[default]
region = eu-central-1
```


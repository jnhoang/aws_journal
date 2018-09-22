# aws_journal


## install aws

https://docs.aws.amazon.com/cli/latest/userguide/cli-install-macos.html#awscli-install-osx-path


## install python

I don't remember if you really need to install python, attemp to skip the pip step and just install the cli directly please.

install pip
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
sudo -H python get-pip.py

curl "https://s3.amazonaws.com/aws-cli/awscli-bundle.zip" -o "awscli-bundle.zip"
unzip awscli-bundle.zip
sudo ./awscli-bundle/install -i /usr/local/aws -b /usr/local/bin/aws

## configure aws
https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html


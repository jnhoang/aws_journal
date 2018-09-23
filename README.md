<h1>aws_journal</h1>

<h2></h2>
<h2>install aws cli</h2>
<p> https://docs.aws.amazon.com/cli/latest/userguide/installing.html </p>
<p> https://docs.aws.amazon.com/cli/latest/userguide/cli-install-macos.html#awscli-install-osx-path </p>

<code>
  curl "https://s3.amazonaws.com/aws-cli/awscli-bundle.zip" -o "awscli-bundle.zip"  <br/>
  unzip awscli-bundle.zip  <br/>
  sudo ./awscli-bundle/install -i /usr/local/aws -b /usr/local/bin/aws
</code>

<h2>configure aws</h2>
<p>https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html</p>

<h2>test</h2>
<p>aws ec2 describe-instances --output table --region us-west-2</p>

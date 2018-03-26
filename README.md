# AwsLambdaTesting_01
AwsLambdaTesting_01 testing lambda functions in AWS.

to make this work:

<pre>
git clone git@github.com:balihoo-krice/AwsLambdaTesting_01.git
cd to AwsLambdaTesting_01
pyenv local 3.6.1  #so you get a non-blambda python in this directory
pip install awscli
</pre>

Next, need to configure AWS CLI to work with your keys.
spelled out in https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html

Follow these directions to set up your credentials.  This involves logging into AWS https://console.aws.amazon.com/iam/home?#/users/krice@balihoo.com?section=security_credentials   (your username instead) and looking at the credentials, then entering aws configure command and cutting/pasting the access_key_id and aws_secret_access_key values appropriately from the IAM location.  We are in us-east-1 (default).  You don't have to choose a default output format, so [None] is okay.

Example interaction (values changed to protect the innocent):
<pre>

aws configure
CHIEMPML010013:~/Projects/AwsLambdaTesting_01] aws configure
AWS Access Key ID [****************FSMQ]: A2345678901234567890
AWS Secret Access Key [****************v2wP]: a234567890123456789012345678901234567890 
Default region name [us-east-1]:
Default output format [None]:
[CHIEMPML010013:~/Projects/AwsLambdaTesting_01]
</pre>



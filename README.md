## Laundry Hero Demo App

## Getting started with chalice

1. Setup AWS credentials
````
$ mkdir ~/.aws
$ cat >> ~/.aws/config
[default]
aws_access_key_id=YOUR_ACCESS_KEY_HERE
aws_secret_access_key=YOUR_SECRET_ACCESS_KEY
region=YOUR_REGION (such as us-west-2, us-west-1, etc)
````

2. Create your project
````
$ chalice new-project helloworld && cd helloworld
````

3. Deploy your service
````
chalice deploy
````

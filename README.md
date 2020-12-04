# anzibl

anzibl is a devops assignment for an internship at sendpost.io. The objectives are as follows:

#### Create an ansible script that does the following:

- [ ] Create a small EC2 or DO Instance
- [ ] Run a small HTTP server (preferably in Golang) with a ping endpoint
- [ ] Run prometheus on the same machine to monitor ping endpoint and raise an alert over email when either:
	- HTTP server process is crashed
	- Ping endpoint is not responding

#### With the following features being great to haves / bonuses:

- [ ] Make the whole thing idempotent

#### Breaking down the task into atomic steps

- [x] Read up on ansible for a quick primer
- [x] Setup a sensible initial directory structure
- [ ] Find resources for deploying to AWS with Ansible
- [ ] Create a small EC2 instance
- [ ] Read up on how to write a HTTP Server in Golang
- [ ] Write the server with a ping endpoint
- [ ] Add it to ansible
- [ ] Figure out how to monitor my server with prometheum
- [ ] Setup the alerts in prometheus
- [ ] Automate with ansible

#### Steps takes

- [x] Explore what ansible is, it's common use cases, best practices and read the getting started part of the docs
- [x] The directory structure was taken from ansible's official documentation [here](https://docs.ansible.com/ansible/latest/user_guide/sample_setup.html#sample-directory-layout).
- [x] Found [aws_guide](https://docs.ansible.com/ansible/latest/scenario_guides/guide_aws.html). Create new IAM user and provision `secret_access_key` and `access_id`.
- [x] Install `aws-cli` and configure a work profile with `access_id` and `secret_access_key`.
- [x] Write a playbook that connects to aws and gets me information about total running resources.
- [x] Create a security group in the aws console named `test`
- [x] Write a playbook that creates a `Key Pair` and `Provisions EC2 Instance`

<!-- - [x] The directory structure was taken from ansible's official documentation [here](https://docs.ansible.com/ansible/latest/user_guide/sample_setup.html#sample-directory-layout). -->

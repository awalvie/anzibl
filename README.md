# anzibl

anzibl is a devops assignment for an internship at sendpost.io. The objectives are as follows:

### Create an ansible script that does the following:

- [ ] Create a small EC2 or DO Instance
- [ ] Run a small HTTP server (preferably in Golang) with a ping endpoint
- [ ] Run prometheus on the same machine to monitor ping endpoint and raise an alert over email when either:
	- HTTP server process is crashed
	- Ping endpoint is not responding

### With the following features being great to haves / bonuses:
- [ ] Make the whole thing idempotent

### Breaking down the task into atomic steps

- [ ] Read up on ansible for a quick primer
- [ ] Setup a sensible initial directory structure
- [ ] Find resources for deploying to AWS with Ansible
- [ ] Create a small EC2 instance
- [ ] Read up on how to write a HTTP Server in Golang
- [ ] Write the server with a ping endpoint
- [ ] Add it to ansible
- [ ] Figure out how to monitor my server with prometheum
- [ ] Setup the alerts in prometheus
- [ ] Automate with ansible

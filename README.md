## Standalone JBoss Deployment

Run the playbook, like this:

	ansible-playbook -i hosts site.yml


## Application deployment

Run the playbook using:

	ansible-playbook -i hosts deploy-application.yml
	
The HelloWorld application will be available at `http://<jboss server>:<http_port>/helloworld`

The Ticket Monster application will be available at `http://<jboss server>:<http_port>/ticket-monster`
# jboss-standalone
# jboss-standalone-fixed
# jboss.working

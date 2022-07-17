- Just a simple test to ssh into an EC2 running instance in AWS, through Ansible playbook.
- Configures a simple node server using roles and its corresponding tasks in the steps below:

-- Add a new task file - roles/setup/tasks/main.yml. This task file should contain instructions to:

-- update apt packages
-- upgrade packages
-- install dependencies, such as NodeJS and NPM
-- install pm2
-- create a ~/web directory
-- copy index test page from files/index.js to ~/web/index.js
-- Start the web server using the command pm2 start ~/web/index.js -f


-- Also I have tried also to deploy an EC2 i stance using the Cloud Formation script a seen in the template.yml file.
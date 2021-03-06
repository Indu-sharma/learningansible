@Author : Indu Sharma

@Date : 04-14-2019

Repository Structure
```bash
.
+--- .editorconfig
+--- .gitattributes
+--- .gitignore
+--- ansible.cfg
+--- inventory
|   +--- group_vars
|   +--- hosts
|   +--- host_vars
+--- library
|   +--- test
+--- logs
|   +--- ansible.log
+--- module_utils
|   +--- test
+--- README.md
+--- requirements.txt
+--- requirements.yml
+--- roles
|   +--- mycs
|   |   +--- defaults
|   |   |   +--- main.yml
|   |   +--- files
|   |   +--- handlers
|   |   |   +--- main.yml
|   |   +--- meta
|   |   |   +--- main.yml
|   |   +--- README.md
|   |   +--- tasks
|   |   |   +--- child_tasks.yml
|   |   |   +--- main.yml
|   |   +--- templates
|   |   +--- tests
|   |   |   +--- inventory
|   |   |   +--- test.yml
|   |   +--- vars
|   |   |   +--- main.yml
|   +--- myos
|   |   +--- defaults
|   |   |   +--- main.yml
|   |   +--- files
|   |   +--- handlers
|   |   |   +--- main.yml
|   |   +--- meta
|   |   |   +--- main.yml
|   |   +--- README.md
|   |   +--- tasks
|   |   |   +--- main.yml
|   |   +--- templates
|   |   +--- tests
|   |   |   +--- inventory
|   |   |   +--- test.yml
|   |   +--- vars
|   |   |   +--- main.yml
+--- site.yml
```
@About: This repos demonstrate how to organise ansible projects, playbooks, plays, roles, tasks and re-use the tasks/roles.

@Steps to get started:

```
*Clone the Repos*

*pip install -r requirements.txt

*ansible-galaxy install -r requirements.yml

*ansible-playbook site.yml -vvv

# codemancy-postgres-python
Codemancy template for Postgres / Python / Flask


# local run

docker run --rm -it -v my/staging/codemancy-postgres-python:/ansible/playbooks -v my/staging/codemancy-postgres-python-target:/target factory/ansible-playbook spell.yml
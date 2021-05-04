[![CWL Engines](https://github.com/longr/ansible-cwl/actions/workflows/main.yml/badge.svg)](https://github.com/longr/ansible-cwl/actions)


# Ansible roles for installing CWL engines

Here we have created various ansible tasks to install and test (using molecule) for different CWL engines.

3 of these are working with tests which check whether a simple "Hello World" runs.  Cromwell is close to working, but I cannot get conda to activate.

Reana and galaxy have not been converted to use molecule yet.


## Working

- cwl
- toil
- airflow

## In development

- reana
- cromwell
- galaxy



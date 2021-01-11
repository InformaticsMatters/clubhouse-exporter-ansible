# Clubhouse Exporter Orchestration (Ansible)

![lint](https://github.com/InformaticsMatters/clubhouse-exporter-ansible/workflows/lint/badge.svg)

![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/informaticsmatters/clubhouse-exporter-ansible)

A playbook and Role to deploy the Clubhosue Exporter (**CronJob),
suitable for execution by [AWX].

This project contains one Ansible role:-

*   **clubhouse-exporter**

>   Note: The Role is designed to be executed from within our AWX server
    where credentials for the cluster (Kubernetes) reside. If you're not
    running from AWX (discouraged) then you will need to provide
    values for the variables that would be injected by AWX.

As with all of our playbooks you can find the common user-defined variables
in the role's `defaults/main.yaml` and less common variables in
`vars/main.yaml`.

---

[awx]: https://github.com/ansible/awx

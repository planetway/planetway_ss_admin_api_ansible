# Local development

This role uses molecule for local development. Start by installing it with pip (or any other method on your choice).

```
pip3 install -r requirements.txt
```

Run the full test with `molecule test`.

Use `molecule converge` to run/test playbook itself.

Note about local development environment:
*`enrollment_token` (end-entity password) needs to be set to correct value in
`molecule/default/converge.yml` to avoice client certificate import failure.*

More on [molecule](https://molecule.readthedocs.io/en/latest/).

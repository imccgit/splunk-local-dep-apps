Directory layout
---
* dev-servers	`inventory file containing the server URLs`
* README.md	`this file`
* site.yml	`the main playbook file`

Usage
---
`ansible-playbook -i dev-servers site.yml --connection=local`

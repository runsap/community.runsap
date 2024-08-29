# Ansible Collection - community.runsap

This collection provides roles that are needed to implement the 
runsap methology.

# Capabilities

The collection holds the following roles:

- aws_ami
- sap_inventory
- aws_inventory
- aws_backint
- summary

And the following module:

- play_status


# Develop

## Add a new role to the collection

`ansible-galaxy role init roles/new_role`

## Use commit messages

**Nieuwe Functie** 

`feat(api): voeg gebruikersauthenticatie toe`

**Bugfix** 

`fix(login): herstel fout bij inloggen met speciale tekens`

**Refactor**

`refactor(database): herschrijf database initialisatie`

**Documentatie**
`docs(README): update installatie-instructies` 
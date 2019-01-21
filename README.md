# Work In Progress
# ansible_tower_genie_inventories
An Ansible role to create inventories and inventory sources.


## Variables
| Variable Name | Default Value | Required | Description |
|:---:|:---:|:---:|:---:|
|tower_url| The web url for tower. ex: `"https://prod-cluster.com"`|
|source_project_id| The project ID for to integrate with for setting up the inventory sources to an SCM project. _INTEGER_|
|source_path| The path relative to your repository for the script that should be ran. ex: `"myscript.py"`|
|tower_user| Username of the API user to create inventory objects. Variable set in `vault.yml`.|
|tower_pass| Password of the API user to create inventory objects. Variable set in `vault.yml`.|

# License
[MIT](LICENSE)

# Author
[Edward Quail](mailto:equail@redhat.com)
[Andrew J. Huffman](https://github.com/ahuffman)

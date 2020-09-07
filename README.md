# ansible-sample

## Environment

    $ conda create -n ansible_playbooks python=3.6 --yes
    $ source activate ansible_playbooks
    $ pip install -r requirements.txt

## Run playbook

    $ ansible-playbook maintenance.yml --inventory-file=./inventory

# Citrix ADC ansible configuration

## install the citrix ADC ansible modules

```
ansible-galaxy collection install git+https://github.com/citrix/citrix-adc-ansible-modules.git#/ansible-collections/adc

ansible-galaxy collection build

ansible-galaxy collection install citrix-adc-1.1.0.tar.gz

pip3 install nitro-python-1.0_kamet.tar.gz
```

## Create inventory file for Citrix ADC devices

## Configure variables to match the environment

## run the playbook

```
ansible-playbook ctxadc_ldaps.yaml -i inventory.yaml
```

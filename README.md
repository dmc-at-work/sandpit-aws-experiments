# Project: NGDC

<br />

## Section: AWS

<br />

#### Subsection: Organization

##### Creation / Revision / Maintenance
* From another repo developed separately
##### Deletion
* From another repo developed separately
##### How
* ```From another repo developed separately```

<br />

#### Subsection: VPC

##### Creation / Revision / Maintenance
* *playbook-vpc-[public-subnet-count]-[private-subnet-count]-subnet*
* playbook-vpc-create-0-0-subnet
* playbook-vpc-create-0-1-subnet
* playbook-vpc-create-1-0-subnet
* playbook-vpc-create-1-1-subnet
* playbook-vpc-create-2-2-subnet
* playbook-vpc-create-0-0-subnet-sts
* playbook-vpc-create-0-1-subnet-sts
* playbook-vpc-create-1-0-subnet-sts
* playbook-vpc-create-1-1-subnet-sts
* playbook-vpc-create-2-2-subnet-sts
##### Deletion
* playbook-vpc-delete
* playbook-vpc-delete-sts
##### How
* ```ansible-playbook playbook-vpc-create-0-0-subnet.yml -i inventory```
* ```ansible-playbook playbook-vpc-create-0-1-subnet.yml -i inventory```
* ```ansible-playbook playbook-vpc-create-1-0-subnet.yml -i inventory```
* ```ansible-playbook playbook-vpc-create-1-1-subnet.yml -i inventory```
* ```ansible-playbook playbook-vpc-create-2-2-subnet.yml -i inventory```
* ```ansible-playbook playbook-vpc-delete.yml -i inventory```
* ```ansible-playbook playbook-vpc-create-0-0-subnet.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-create-0-1-subnet.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-create-1-0-subnet.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-create-1-1-subnet.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-create-2-2-subnet.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-delete.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-create-0-0-subnet-sts.yml -i inventory```
* ```ansible-playbook playbook-vpc-create-0-1-subnet-sts.yml -i inventory```
* ```ansible-playbook playbook-vpc-create-1-0-subnet-sts.yml -i inventory```
* ```ansible-playbook playbook-vpc-create-1-1-subnet-sts.yml -i inventory```
* ```ansible-playbook playbook-vpc-create-2-2-subnet-sts.yml -i inventory```
* ```ansible-playbook playbook-vpc-delete-sts.yml -i inventory```
* ```ansible-playbook playbook-vpc-create-0-0-subnet-sts.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-create-0-1-subnet-sts.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-create-1-0-subnet-sts.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-create-1-1-subnet-sts.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-create-2-2-subnet-sts.yml -i inventory -vvvv```
* ```ansible-playbook playbook-vpc-delete-sts.yml -i inventory -vvvv```

<br />

#### Subsection: Audit

##### Creation / Revision / Maintenance
* audit-create
* audit-update
* audit-create-sts
* audit-update-sts
##### Deletion
* audit-delete
* audit-delete-sts
##### How
* ```ansible-playbook playbook-audit-create.yml -i inventory```
* ```ansible-playbook playbook-audit-delete.yml -i inventory```
* ```ansible-playbook playbook-audit-update.yml -i inventory```
* ```ansible-playbook playbook-audit-create.yml -i inventory -vvvv```
* ```ansible-playbook playbook-audit-delete.yml -i inventory -vvvv```
* ```ansible-playbook playbook-audit-update.yml -i inventory -vvvv```
* ```ansible-playbook playbook-audit-create-sts.yml -i inventory```
* ```ansible-playbook playbook-audit-delete-sts.yml -i inventory```
* ```ansible-playbook playbook-audit-update-sts.yml -i inventory```
* ```ansible-playbook playbook-audit-create-sts.yml -i inventory -vvvv```
* ```ansible-playbook playbook-audit-delete-sts.yml -i inventory -vvvv```
* ```ansible-playbook playbook-audit-update-sts.yml -i inventory -vvvv```

<br />

#### Subsection: Security

##### Creation / Revision / Maintenance
* xyz
##### Deletion
* xyz
##### How
* ```foobar```

<br />

#### Subsection: Instance Provisioning

##### Creation / Revision / Maintenance
* xyz
##### Deletion
* xyz
##### How
* ```foobar```

<br />


...
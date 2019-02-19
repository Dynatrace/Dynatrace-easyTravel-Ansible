# Dynatrace-easyTravel-Ansible

This Ansible role installs the Dynatrace [easyTravel Demo Application](https://community.dynatrace.com/community/display/DL/Demo+Applications+-+easyTravel) with the artifacts in the `files` folder.

## Dynatrace easyTravel Components

##### MongoDB

A [MongoDB](https://www.mongodb.org/) database pre-populated with easyTravel data.

##### Apache Tomcat (Business Backend)

An [Apache Tomcat](http://tomcat.apache.org/) instance running the easyTravel Business Backend component listening on port 8091.

##### Apache Tomcat (Customer Frontend)

An [Apache Tomcat](http://tomcat.apache.org/) instance running the easyTravel Customer Frontend component listening on port 8080.

##### NGINX

An [NGINX](http://www.nginx.org) reverse-proxy sitting in front of the Customer Frontend listening on port 80.

## Sample Usage

1) Add the hosts you wish to into Ansible's `hosts` file  
2) Adapt the `remote_user` directive in `ansible.cfg`  
3) Run `ansible-playbook -i hosts playbook.yml`

## Additional Resources

- [Dynatrace-easyTravel-Docker](https://github.com/dynaTrace/Dynatrace-easyTravel-Docker): the Dynatrace easyTravel Demo Application inside Docker

## Questions?

Feel free to post your questions on the Dynatrace Community's [Continuous Delivery Forum](https://answers.dynatrace.com/spaces/148/open-q-a_2.html?topics=continuous%20delivery).

## License

Licensed under the MIT License. See the LICENSE file for details.
[![analytics](https://www.google-analytics.com/collect?v=1&t=pageview&_s=1&dl=https%3A%2F%2Fgithub.com%2FdynaTrace&dp=%2FDynatrace-easyTravel-Ansible&dt=Dynatrace-easyTravel-Ansible&_u=Dynatrace~&cid=github.com%2FdynaTrace&tid=UA-54510554-5&aip=1)]()

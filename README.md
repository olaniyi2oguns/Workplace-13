# ANSIBLE DYNAMIC ASSIGNMENTS (INCLUDE) AND COMMUNITY ROLES

**OBJECTIVE OF THE PROJECT:**

The objective of this project is to further enhance your knowledge and skills in Ansible by introducing dynamic assignments using the include module. The project builds upon the concepts and modules learned in the [workplace-11](https://github.com/olaniyi2oguns/Workplace-11.git) and [Workplace-12](https://github.com/olaniyi2oguns/Workplace-12.git), focusing on the configuration of UAT servers. The project aims to differentiate between static and dynamic assignments. Static assignments are achieved using the import Ansible module, as demonstrated in [Workplace-12](https://github.com/olaniyi2oguns/Workplace-12.git). In contrast, dynamic assignments utilize the include module. When the import module is used, all statements are pre-processed during playbook parsing. This means that when the site.yml playbook is executed, Ansible processes all the referenced playbooks during the parsing stage. Any changes made to the statements during execution are not considered, making it a static assignment. In contrast, when the include module is used, statements are processed only during the execution of the playbook. Any changes encountered in the statements during execution are considered and utilized. It is important to note that static assignments are generally recommended for playbooks as they provide more reliability. Dynamic assignments, due to their dynamic nature, can make playbook debugging challenging. However, dynamic assignments can be useful for environment-specific variables, which will be introduced in this project.






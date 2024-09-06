- name: Play-01
  hosts: web #which hosts your ansible wants to connect
  vars:
    NAME: Manohar
  tasks: #list of tasks/modules/collections
  - name: ping the server
    ansible.builtin.debug:
      msg: "Name is {{NAME}}"
  - name: ping the server
    vars:
     NAME: Lucky
    ansible.builtin.debug:
      msg: "Name is {{NAME}}"
  - name: ping the server
    ansible.builtin.debug:
      msg: "Name is {{NAME}}"

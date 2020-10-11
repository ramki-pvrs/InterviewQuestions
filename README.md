# InterviewQuestions
Welcome to This repository
---
- name: Installation of Nginx
  hosts: webservers
  tasks:
    - git:
       repo: 'https://github.com/anujdevopslearn/MavenBuild'
       dest: /opt/
       version: master
    - name: return motd to registered var
      command: ls -lart /opt/

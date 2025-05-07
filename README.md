# Ansible Role: apache_custom_port

Install and configure Apache (`httpd`) to run on port `88` with SELinux and firewalld configured.

## Author

Marwan Ghonem

## Usage

```yaml
- hosts: webservers
  roles:
    - apache_custom_port
```

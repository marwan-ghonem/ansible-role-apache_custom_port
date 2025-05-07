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

## apache_custom_port
├── defaults/

│   └── main.yml# Default variables

├── files/
│   └── index.html      # Web page to deploy

├── meta/
│   └── main.yml        # Role metadata

├── tasks/
│   └── main.yml        # Main task list

└── README.md           # Role documentation


## ![servera](https://github.com/user-attachments/assets/594e0c1c-9cc1-4eb3-9297-d3d5cf907a9a)

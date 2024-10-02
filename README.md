# Ways-to-Clone-a-Git-Repository
Ways to Clone a Git Repository
**Prerequisites**

1. Create Amazon Linux 2 EC2 instance
2. ssh into the EC2 instance

```
ssh -i
```

1. Install the git package using yum on the Amazon Linux 2 server.

```
sudo yum install git
```

**Clone a git repository**

- to clone a git repository from GitHub
    
    ```
    git clone <HTTPS_URL>
    ```
    
- to clone
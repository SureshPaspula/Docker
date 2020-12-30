## Dockerfile with Nginx App

# Can build Docker image by using this Dockerfile
  It has following tools:
  ```
    . PHP
    . curl , git , vim, ping , pip , python
    . Used ssh-keygen for password less authentication
  ```

# Steps to build Image
```
  docker image build -t image:latest ./(path of the dockerfile)
```

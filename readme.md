
# Nginx load balancing

This is a simple python flask application for implementing the load balancing feature of nginx


## Deployment

To run this project

```bash
  ## You need docker and docker-compose installed in your machine ##

  docker-compose up -d --build --scale app=3

  ## After running the project login in to nginx container ##
  ## Change your ip addresses according to yours in /etc/nginx/nginx.conf ##
  ## After that just reload nginx from inside the container ##

  nginx -s reload
```

## 🚀 About Me
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://bd.linkedin.com/in/rifat0)


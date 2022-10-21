# Notes

```bash
echo "127.0.0.1 myapp.com" >> sudo tee -a /etc/hosts
docker-compose -f ./conf/docker-compose.yml -p "bitnami-nginx-stack" up -d
docker-compose -f ./conf/docker-compose.yml -p "bitnami-nginx-stack" down
```

You can visit either [http://myapp.com](http://myapp.com) or [https://myapp.com](https://myapp.com).

## References

[Create An EMP Development Environment With Bitnami Containers](https://docs.bitnami.com/containers/how-to/create-emp-environment-containers/)

[Create An AMP Development Environment With Bitnami Containers](https://docs.bitnami.com/containers/how-to/create-amp-environment-containers/)

[Enable HTTPS Support With NGINX](https://docs.bitnami.com/aws/infrastructure/nginx/administration/enable-https-ssl-nginx/)

[stack name with docker-compose](https://stackoverflow.com/questions/53401672/stack-name-with-docker-compose)

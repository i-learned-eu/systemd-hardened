Do not forget to run the following commands to make this service work

```sh
sudo setcap 'cap_net_bind_service=+ep' /usr/sbin/nginx

sudo mkdir /var/run/nginx
sudo chown nginx:nginx /var/run/nginx/
```

Tested with nginx/1.20.2 score of 1.9 (was 9.2) initially !

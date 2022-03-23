# install verdaccio

```
npm i -g verddaccio
```

verddaccio is npm proxy server and cach


# install pm2

```
npm i -g pm2
```

pm2 is prossus manager for node and python ... apps

# start verdaccio as daemon

```
pm2 start `which verdaccio`
```
# run pm2 and his processus on system startup

```
pm2 startup systemd
```

this command will print something like this
```
utput
[PM2] Init System found: systemd
sammy
[PM2] To setup the Startup Script, copy/paste the following command:
sudo env PATH=$PATH:/usr/bin /usr/lib/node_modules/pm2/bin/pm2 startup systemd -u sammy --hp /home/sammy
```
on the console
run the above command

then

```
pm2 save

```
# Setup

Add to your hosts file (for the sake of the demo)
```shell
sudo su
echo "127.0.0.1 local.chardskarth.me\n127.0.0.1 localgollum.chardskarth.me" >> /etc/hosts
```

# Run
docker compose up


# Test
http://localhost:3003/gollum/create/Home -> works (normal scenario)

http://localhost:3004/gollum/create/Home -> works (normal scenario with base path)

http://localgollum.chardskarth.me:3002/ -> not working

http://local.chardskarth.me:3002/gollum -> not working (with basepath)


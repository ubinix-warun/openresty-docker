Getting started with Lua web development using docker as your Lua web application server [https://github.com/torhve/openresty-docker]

```

docker pull ubinix5warun/openresty-docker

```

```

docker build -t="ubinix-warun/openresty-docker" .

# ubuntu 16.04 and openresty 1.11.2.2
mkdir logs

docker run -t -i -p 8080:8080 -v=`pwd`:/helloproj -w=/helloproj ubinix-warun/openresty-docker

```
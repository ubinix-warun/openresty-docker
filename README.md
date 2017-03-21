Getting started with Lua web development using docker as your Lua web application server [https://github.com/torhve/openresty-docker]

```

docker pull ubinix5warun/openresty-docker

git clone https://github.com/ubinix-warun/openresty-docker.git
cd openresty-docker

mkdir logs
docker run -t -i -p 8080:8080 -v=`pwd`:/helloproj -w=/helloproj ubinix5warun/openresty-docker

```

```

git clone https://github.com/ubinix-warun/openresty-docker.git
cd openresty-docker

docker build -t="ubinix-warun/openresty-docker" .

# docker-hub, ubuntu 16.04 and openresty 1.11.2.2

mkdir logs
docker run -t -i -p 8080:8080 -v=`pwd`:/helloproj -w=/helloproj ubinix-warun/openresty-docker

```
## run dokcer

```
docker up -d --force-recreate --build
```

## success install package

```
cd client
npm login --registry=http://localhost:80/
# sacru2red / sacru2red
npm install
```

## faile install package

toggle comment /apache/Dockerfile
7 line

```
docker up -d --force-recreate --build
cd client
rm -rf node_modules
npm cache clean --force
npm install
```

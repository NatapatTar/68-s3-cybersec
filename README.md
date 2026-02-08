# Cyber security

## Owner
- 6702041511179
- Natapat Ngernhoy
- s6702041511179@email.kmutnb.ac.th

## Enviroment
```sh
cp env.siple .env
```

## Running services
### Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # background
```

## Admin
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```

## App
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```
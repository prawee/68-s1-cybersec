# Cyber Security

## Information
- Prawee Wongsa (POD)
- 4820750141
- prawee.w@fte.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```

## Service running
### Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # background
```

### Admin
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```
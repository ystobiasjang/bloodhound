## BloodHound Docker (PostgreSQL only)

### Access
- URL: `http://[host]:8080`
- Username: `admin`
- Password: `1`

### Up
```bash
docker compose up -d
```

### Down
```bash
docker compose down -v
```

### Update to the latest version
```bash
docker compose down -v
docker compose up -d --pull always
# Optional: remove dangling images
docker image prune -f
```
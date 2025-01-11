# traefik-all-static

export HASHED_PASSWORD=$(openssl passwd -apr1)

admin

---

docker stack deploy -c traefik-host.yml traefik

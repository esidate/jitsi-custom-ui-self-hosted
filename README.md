# Jitsi Meet Custom UI and Self-Hosted

### Setup

```sh
cp env.example .env
./gen-passwords.sh
mkdir -p ~/.jitsi-meet-cfg/{web/crontabs,web/letsencrypt,transcripts,prosody/config,prosody/prosody-plugins-custom,jicofo,jvb,jigasi,jibri}
docker-compose up -d
```

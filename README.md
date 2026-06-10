# Netflix Blocklist para Pi-hole

Lista de bloqueio completa para bloquear o Netflix em toda a sua rede usando o Pi-hole.

## 📥 Adicionar ao Pi-hole

Adicione a URL abaixo em **Group Management → Adlists** no seu Pi-hole:
https://raw.githubusercontent.com/elsimarcoelho/netflix-blocklist/refs/heads/main/netflix-blocklist.txt

Depois clique em **Update Gravity**.

## 📋 Domínios Bloqueados

A lista bloqueia domínios principais, streaming, CDNs, APIs e telemetria do Netflix, incluindo:

- `netflix.com`, `netflix.net`
- `nflxvideo.net`, `nflxso.net`, `nflximg.com`, `nflxext.com`
- `*.oca.nflxvideo.net` (CDNs)
- `android13.*.netflix.com`, `ios.prod.ftl.netflix.com`
- `ichnaea.netflix.com`, `logging.netflix.com` (telemetria)

## 🔄 Atualização

A lista é atualizada automaticamente quando você roda `pihole -g` no Pi-hole.

## 📅 Última atualização

2026-06-10

## 📝 Licença

MIT

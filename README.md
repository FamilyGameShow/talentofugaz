# FUGAZ - Talento Fugaz
> El talento pasa rápido. No lo dejes ir.

Plataforma para artistas callejeros de La Plata.
Un artista prende vivo desde el semáforo (7 y 50), genera un QR y un link público. El que pasa escanea y deja propina por MercadoPago aunque el artista ya se haya ido.

### Problema
El artista callejero solo gana si la gente tiene monedas en el momento. 90% se va sin dejar nada.

### Solución FUGAZ
1. Artista prende vivo con un click
2. Se genera QR + Link público `fugaz.ar/id`
3. El público escanea y ve el vivo + deja propina por MP

### Demo en vivo
🔴 [https://TU_USUARIO.github.io/talentofugaz/](https://TU_USUARIO.github.io/talentofugaz/)

### Stack v2 (prototipo)
- HTML Single File
- Firebase Firestore (signaling WebRTC)
- WebRTC para vivo real P2P
- MercadoPago Alias Link
- QR API

### Roadmap
- [x] v1: QR + MP local
- [x] v2: Vivo real P2P + Link compartible
- [ ] v3: Mapa en vivo de La Plata + Split de pagos 10%
- [ ] v4: App + Historial de talentos fugaces

Hecho en La Plata, AR.

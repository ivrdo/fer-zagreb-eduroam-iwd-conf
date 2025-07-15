# fer-zagreb-eduroam-iwd-conf

IWD konfiguracija za Eduroam na FER-u.

Potrebno je kopirati `eduroam.8021x` u `/var/lib/iwd/` i `eduroam.pem` u `/etc/iwd/`.

Potrebno je zamijeniti linije

`
EAP-TTLS-Phase2-Identity=fer_korisniscko_ime@fer.hr
EAP-TTLS-Phase2-Password=fer_lozinka
`

s vlastitim korisničkim imenom i lozinkom.

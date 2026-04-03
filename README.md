# -onfigure-a-wireless-network
(EN) Packet Tracer lab: configure a wireless router and an access point, secure a 2.4 GHz WLAN (WPA2/AES), connect wired/wireless clients, verify connectivity, and perform basic admin hardening plus DHCP/subnet update.
# Packet Tracer Lab — Configure a Wireless Network (WLAN) (EN)

## About
Cisco Packet Tracer lab focused on configuring a WLAN using a wireless router and an access point, connecting wired/wireless clients, and verifying end-to-end connectivity.

## What I did / learned
- Connected an admin PC to a wireless router (wired LAN) and obtained network settings via DHCP
- Logged into the router’s web GUI and adjusted core settings
- Configured WLAN (2.4 GHz): SSID, channel selection, and WPA2 security (AES)
- Connected multiple wireless clients to the WLAN and verified connectivity with a web test
- Added and configured an Access Point (AP) to extend wireless coverage (same SSID/security)
- Performed basic admin hardening: changed default management password
- Migrated the LAN addressing/DHCP scope to a new subnet and renewed client leases
- Observed/validated client roaming behavior between WR and AP based on signal strength

## Verification
- Clients successfully join the WLAN and receive valid IP configuration
- Web connectivity check succeeds from wired and wireless devices
- After subnet/DHCP change, clients renew and connectivity remains OK

## Artifacts (optional)
- `.pkt` topology file
- screenshots of key configs + connectivity checks

---

# Packet Tracer Labor — WLAN konfigurieren (DE)

## Überblick
Cisco Packet Tracer Labor mit Fokus auf WLAN-Konfiguration über einen WLAN-Router und einen Access Point, Anbindung von kabelgebundenen/kabellosen Clients und End-to-End-Verifikation.

## Was ich gemacht / gelernt habe
- Admin-PC per LAN an den WLAN-Router angeschlossen und IP-Konfiguration via DHCP bezogen
- In die Web-GUI des Routers eingeloggt und Grundeinstellungen angepasst
- WLAN (2,4 GHz) konfiguriert: SSID, Kanalwahl und WPA2-Sicherheit (AES)
- Mehrere WLAN-Clients verbunden und Konnektivität per Web-Test verifiziert
- Access Point (AP) hinzugefügt/konfiguriert, um die WLAN-Abdeckung zu erweitern (gleiche SSID/Sicherheit)
- Admin-Härtung: Standard-Management-Passwort geändert
- LAN-Adressierung/DHCP-Bereich auf ein neues Subnetz migriert und Client-Leases erneuert
- Roaming-Verhalten zwischen WR und AP anhand der Signalstärke beobachtet/verifiziert

## Verifikation
- Clients treten dem WLAN bei und erhalten eine gültige IP-Konfiguration
- Web-Konnektivität funktioniert von kabelgebundenen und kabellosen Geräten
- Nach Subnetz/DHCP-Änderung: Lease erneuern, Konnektivität bleibt stabil

## Artefakte (optional)
- `.pkt` Datei
- Screenshots: Konfiguration + Tests

---

# Лабораторная — Настройка беспроводной сети (WLAN) в Packet Tracer (RU)

## Описание
Лабораторная в Cisco Packet Tracer по настройке WLAN через беспроводной роутер и точку доступа, подключению проводных/беспроводных клиентов и проверке сквозной связности.

## Что делал / чему научился
- Подключил Admin-ПК к беспроводному роутеру по LAN и получил параметры по DHCP
- Зашёл в веб-интерфейс роутера и изменил базовые настройки
- Настроил WLAN (2.4 GHz): SSID, выбор канала и безопасность WPA2 (AES)
- Подключил несколько беспроводных клиентов и проверил доступность по web-тесту
- Добавил и настроил точку доступа (AP) для расширения покрытия (та же SSID/безопасность)
- Выполнил админ-усиление: сменил стандартный пароль управления
- Перевёл LAN-адресацию/пул DHCP на другую подсеть и обновил аренду адресов у клиентов
- Наблюдал/подтвердил роуминг клиента между WR и AP по уровню сигнала

## Проверка
- Клиенты подключаются к WLAN и получают корректную IP-конфигурацию
- Web-проверка проходит с проводного и беспроводных устройств
- После смены подсети/DHCP: renew → связность сохраняется

## Артефакты (опционально)
- `.pkt` файл топологии
- скриншоты настроек и проверок

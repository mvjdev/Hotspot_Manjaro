# Hotspot_Manjaro

```
sudo systemctl status NetworkManager
```

```
sudo systemctl start NetworkManager
```
CRÉER LE HOTSPOT
```
sudo nmcli device wifi hotspot con-name Maria ssid 'STD(HE)' band bg password MVJ:71042
```
POUR VOIR LE MOT DE PASSE
```
nmcli dev wifi show-password
```
POUR VOIR LES RÉSEAUX CONNECTER
```
nmcli device
```
POUR VOIR LES RÉSEAUX QUI A PASSÉ SUR L'ORDI
```
nmcli connection show
```

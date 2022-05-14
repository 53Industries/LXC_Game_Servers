# Download - Updated 2022/5/14
  - https://lxc.frozenserver.tech/game/css/base_meta_sm.tar.gz
# Users
  - root/admin
  - steam/steam

# Server Control
  - systemctl start css
  - systemctl restart css
  - systemctl enable css
  - Will Check for updates on start

# First boot changes
  - Change root/steam password
  - Update Server.cfg settings /home/steam/SteamCMD/css/cstrike/config/server.cfg
    - hostname ""
    - rcon_password ""
  - Update autoexec.cfg settings /home/steam/SteamCMD/css/cstrike/config/autoexec.cfg
    - sv_setsteamaccount "" (https://steamcommunity.com/dev/managegameservers)
  - Update admins for SourceMod /home/steam/SteamCMD/css/cstrike/addons/sourcemod/configs/admin_simple.ini
    - Add user to admin simple

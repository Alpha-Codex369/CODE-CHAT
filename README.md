<h2 align="center"> <img src="https://raw.githubusercontent.com/DARK-H4CKER01/DX-SIMU/refs/heads/main/Dx-simu.jpg" width="470" /> </h2>

<p align="center">

<p align="center"><b>GLOBAL CHAT</b <code></code></p>



## INSTALL WITH TERMUX & LINUX:

```
( trap 'rm -rf "$HOME/CODE-CHAT"' EXIT INT TERM HUP; cd $HOME; IS_TMX=$([ -n "$TERMUX_VERSION" ] && echo 1 || echo 0); SUDO=$([ "$IS_TMX" = "1" ] && echo "" || echo "sudo"); BIN=$([ "$IS_TMX" = "1" ] && echo "$PREFIX/bin" || echo "/usr/local/bin"); FDIR=$([ "$IS_TMX" = "1" ] && echo "$HOME/.termux" || echo "$HOME/.local/share/fonts"); $SUDO apt-get update -qq -y >/dev/null 2>&1; $SUDO apt-get upgrade -qq -y >/dev/null 2>&1; $SUDO apt-get install -qq -y python3 python3-pip git wget >/dev/null 2>&1; pip3 install -q rich requests --break-system-packages >/dev/null 2>&1 || pip3 install -q rich requests >/dev/null 2>&1; rm -rf "$HOME/.toolx"; mkdir -p "$FDIR"; if [ ! -f "$FDIR/font.ttf" ]; then wget -qO "$FDIR/font.ttf" "https://github.com/Alpha-Codex369/CODEX/raw/refs/heads/main/files/font.ttf"; [ "$IS_TMX" = "1" ] && termux-reload-settings || fc-cache -f >/dev/null 2>&1; fi; rm -rf "$HOME/CODE-CHAT"; git clone -q https://github.com/Alpha-Codex369/CODE-CHAT.git >/dev/null 2>&1 && cd CODE-CHAT && $SUDO cp chat "$BIN/chat" && $SUDO chmod +x "$BIN/chat"; g='\033[1;92m'; n='\033[0m'; c='\033[1;96m'; echo -e "\n ${g}[${n}✓${g}] ${c}Type: ${g}chat${n}\n" )
```

### RUN :

```
chat
```

<details id="missing-code-coverage">
  <summary>Use Tool</summary>

##### How to use CODE-CHAT

```

```

</details>
  

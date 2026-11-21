# Hyprland Configuration

Raccolta di configurazioni personali per un ambiente desktop Linux basato su Hyprland e shell Zsh.

## File disponibili

- `hyprland.conf`: configurazione del window manager
- `kitty.config`: impostazioni del terminale Kitty
- `starship.toml`: personalizzazione del prompt Starship
- `.zshrc config`: configurazione della shell

## Utilizzo

I file sono un riferimento per ricostruire l'ambiente originale o trasferirne singole impostazioni su un'altra macchina. Prima di copiarli, leggere i contenuti e verificare percorsi locali, monitor, scorciatoie da tastiera, font e programmi richiamati.

Esempio di installazione per la configurazione di Hyprland:

~~~bash
mkdir -p ~/.config/hypr
cp hyprland.conf ~/.config/hypr/hyprland.conf
~~~

Le configurazioni di Kitty e Starship vanno collocate nelle rispettive directory utente, adattandole alla propria distribuzione.

## Compatibilità

Configurazione personale, non un installer automatico. Alcuni comandi e opzioni dipendono dalle versioni dei programmi e dall'ambiente Linux utilizzato.


[EN]
@HiroshimanRise
#anonym8 (Privacy Friend)

#Sets transparent Proxy tunnel through Tor, I2P, Privoxy, Polipo and modify DNS, for a simple and better privacy and security;
#Include Anonymizing Relay Monitor (arm), macchanger and wipe (Cleans ram/cache & swap-space) features.
#Tested on #Debian #Kali #Parrot
#Feel free to edit and share this script for Liberty and Privacy! ;)

Script requirements are:

-Tor        
-macchanger 
-resolvconf 
-dnsmasq    
-polipo     
-privoxy    
-i2p        
-arm        
-libnotify  
-curl
-bleachbit

they'll be automatically installed.

Open a root terminal and type:

cd anonym8_directory I.Ex: cd /home/toto/Desktop/anonym8-master

then:
chmod +x INSTALL.sh

and:
bash INSTALL.sh

you're done!

For more security, use Firefox!


here's some useful Firefox add on:

profil manager       => https://ftp.mozilla.org/pub/utilities/profilemanager/1.0/   
random agent spoofer => https://addons.mozilla.org/en-US/firefox/addon/random-agent-spoofer/    
no script            => https://addons.mozilla.org/en-US/firefox/addon/noscript/   
ublock origin        => https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/  
HTTPS everywhere     => https://addons.mozilla.org/fr/firefox/addon/https-everywhere/    

Reboot your system and enjoy!

usage:

Basic mode (in a root terminal):

    anON  => Automated protection [ON]
    anOFF => Automated protection [OFF]

Advanced mode (in a root terminal):

    ----[ Tor Tunneling related features ]----
     anonym8 start          => Start Tor Tunneling    
     anonym8 stop           => Stop Tor Tunneling
     anonym8 change         => Changes identity restarting TOR
     anonym8 status         => Tor Tunneling Status
    ----[ IP related features ]----
     anonym8 status_ip      => IP status
    ----[ I2P related features ]----
     anonym8 start_i2p      => Start i2p services
     anonym8 stop_i2p       => Stop i2p services
     anonym8 status_i2p     => i2p status
    ----[ privoxy related features ]----
     anonym8 start_privoxy  => Start privoxy services
     anonym8 stop_privoxy   => Stop privoxy services
     anonym8 status_privoxy => privoxy status
    ----[ polipo related features ]----
     anonym8 start_polipo   => Start polipo services
     anonym8 stop_polipo    => Stop polipo services
     anonym8 status_polipo  => Polipo status
    ----[ macchanger related features ]----
     anonym8 start_mac      => Start macchanger services
     anonym8 stop_mac       => Stop macchanger services
     anonym8 status_mac     => macchanger status
    ----[ arm related features ]----
     anonym8 start_arm      => Start Monitoring Anonymizing Relay (arm)
    ----[ wipe related features ]----
     anonym8 wipe           => cache, RAM & swap-space cleaner

[FR]
@HiroshimanRise
#anonym8 (Privacy Friend)

Établi un tunnel proxy transparent à travers Tor, I2P, Privoxy, Polipo et modifie les DNS;
Inclue la fonction Anonymizing Relay Monitor (arm), macchanger et wipe (effacement de la ram et du swap);
Testé sous #Debian #Kali #Parrot;
Je vous encourage à améliorer et partager ce soft pour la liberté et le respect de la vie privée.

Pour le bon fonctionnement du script, les paquets suivants seront automatiquement installés:

-Tor        
-macchanger
-resolvconf
-dnsmasq    
-polipo     
-privoxy    
-i2p        
-arm        
-libnotify  
-curl
-bleachbit

Pour l'installation, ouvrez un terminal root et tapez:

cd chemin_du_dossier_anonym8  ex: cd /home/toto/Desktop/anonym8-master

puis:
chmod +x INSTALL.sh

puis:
bash INSTALL.sh

le script va maintenant installer les composants nécessaires, répondez juste par oui ou non aux éventuelles questions.

Pour plus de sécurité et par souci d'éthique, je vous recommande d'utiliser Firefox.

Voici une liste d'add on Firefox pour garantir une sécurité minimum (vous êtes libre de vos choix):

-profil manager       => https://ftp.mozilla.org/pub/utilities/profilemanager/1.0/  
-random agent spoofer => https://addons.mozilla.org/en-US/firefox/addon/random-agent-spoofer/   
-no script            => https://addons.mozilla.org/en-US/firefox/addon/noscript/   
-ublock origin        => https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/  
-HTTPS everywhere     => https://addons.mozilla.org/fr/firefox/addon/https-everywhere/  

Rebootez votre systême, vous êtes désormais prêt(e)s à affronter la jungle des interwebs en mode "survival_horror", enjoy!

usage:

Mode basique (Dans un terminal root):

    anON  => protection Automatisée [ON]
    anOFF => protection Automatisée [OFF]

Mode avancé (Dans un terminal root):

    ----[ Tor Tunneling related features ]----
     anonym8 start          => Start Tor Tunneling      
     anonym8 stop           => Stop Tor Tunneling
     anonym8 change         => Changes identity restarting TOR
     anonym8 status         => Tor Tunneling Status
    ----[ IP related features ]----
     anonym8 status_ip      => IP status
    ----[ I2P related features ]----
     anonym8 start_i2p      => Start i2p services
     anonym8 stop_i2p       => Stop i2p services
     anonym8 status_i2p     => i2p status
    ----[ privoxy related features ]----
     anonym8 start_privoxy  => Start privoxy services
     anonym8 stop_privoxy   => Stop privoxy services
     anonym8 status_privoxy => privoxy status
    ----[ polipo related features ]----
     anonym8 start_polipo   => Start polipo services
     anonym8 stop_polipo    => Stop polipo services
     anonym8 status_polipo  => Polipo status
    ----[ macchanger related features ]----
     anonym8 start_mac      => Start macchanger services
     anonym8 stop_mac       => Stop macchanger services
     anonym8 status_mac     => macchanger status
    ----[ arm related features ]----
     anonym8 start_arm      => Start Monitoring Anonymizing Relay (arm)
    ----[ wipe related features ]----
     anonym8 wipe           => cache, RAM & swap-space cleaner

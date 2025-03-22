##### English Bellow #####

Petit projet rapide basé sur l'interface de Gaphux : https://gaphux.com/product/grandma3-onpc-command-section/

Objectif : Contrôler le KeyPad de Grand MA avec son téléphone.

Raison : 
  - Faciliter le focus (surtout quand on est seul) 
  - Faciliter la programmation sur Grand MA 3 On PC
  
  La solution de Gaphux fonctionnait bien mais passait par TouchOSC Bridge. 
  Dans notre cas, nous passons directement par OSC.

Comment ça fonctionne : 
  Il y a un script dans TouchOSC qui permet de compiler un message qui s'envoie à la console en OSC lorsque vous faites "Please".
  Vous pouvez voir la commande en cours de rédaction en haut de l'interface.

Mise en place : 
    - Achetez l'app TouchOSC sur votre mobile | https://hexler.net/touchosc
    - Téléchargez le fichier GM3_touchOSC-NumPad.tosc, puis importez-le dans votre app. 
    - Dans TouchOSC, mettez en place l'OSC : 
        o Connexion 1 : UDP 
        o Host : IP DE VOTRE GRAND MA 3 
        o Send port : PORT OSC DE VOTRE GRAND MA 3
        o Receive port : 
    - Dans Grand MA 3, allez dans le menu Réglages > Réseau, puis dans l'onglet Station Control, activez l'OSC Input.
    - Toujours dans Grand MA 3, allez dans le menu : Réglages > IN / OUT, puis dans le menu OSC. Configurez une OSC Data avec le port mis dans TouchOSC. 
    Attention, assurez-vous d'être sur la bonne interface réseau et d'activer les INPUT !


Soyez indulgent, c'est un petit projet personnel pas complètement abouti et commenté. Il n'a pas été réalisé pour être partagé. 
Je le mets ici car j'ai vu quelques personnes demander une petite app similaire.

A quick project based on the Gaphux interface: https://gaphux.com/product/grandma3-onpc-command-section/


### ENGLISH ###

Objective: Control the Grand MA KeyPad with your phone.

Reason:

  - Facilitate focus (especially when you're alone)
  - Ease programming on Grand MA 3 On PC

The Gaphux solution worked well but used TouchOSC Bridge. In our case, we go directly through OSC.

How it works: 
  There is a script in TouchOSC that allows you to compile a message that is sent to the console in OSC when you press "Please."
  You can see the command being written at the top of the interface.

Setup:

  1. Buy the TouchOSC app on your mobile | https://hexler.net/touchosc
  2. Download the GM3_touchOSC-NumPad.tosc file, then import it into your app.
  3. In TouchOSC, set up the OSC: 
      o Connection 1: UDP 
      o Host: IP OF YOUR GRAND MA 3 
      o Send port: OSC PORT OF YOUR GRAND MA 3 
      o Receive port:
  4. In Grand MA 3, go to the Settings > Network menu, then in the Station Control tab, enable OSC Input.
  5. Still in Grand MA 3, go to the Settings > IN / OUT menu, then in the OSC menu. Configure an OSC Data with the port set in TouchOSC. Warning, make sure you're on the correct network interface and have INPUTS enabled!


Be lenient, it's a small personal project that's not fully completed or commented. It wasn't made to be shared. I’m posting it here because I’ve seen a few people ask for a similar app.

Looking forward to it!

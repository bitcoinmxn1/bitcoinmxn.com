---
id: 448
title: Un tutorial muy básico para instalar STEEM para Python
date: 2018-01-22T09:12:27+00:00
author: Lily
layout: post
guid: http://bitcoinmxn.com/?p=448
permalink: /2018/01/22/un-tutorial-muy-basico-para-instalar-steem-para-python/
snap_isAutoPosted:
  - "1516612374"
custom_sidebar:
  - sidebar-single
dsq_thread_id:
  - "6429959340"
top_term:
  - "71"
snap_MYURL:
  - ""
snapEdIT:
  - "1"
snap5P:
  - |
    s:214:"a:1:{i:0;a:8:{s:2:"do";s:1:"1";s:10:"msgTFormat";s:7:"%TITLE%";s:9:"msgFormat";s:18:"%EXCERPT%
    
    %URL%";s:9:"isAutoImg";s:1:"A";s:8:"imgToUse";s:0:"";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"do5P";i:0;}}";
snapLJ:
  - 's:158:"a:1:{i:0;a:6:{s:2:"do";s:1:"0";s:10:"msgTFormat";s:7:"%TITLE%";s:9:"msgFormat";s:9:"%EXCERPT%";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doLJ";i:0;}}";'
snapMD:
  - |
    s:402:"a:1:{i:0;a:10:{s:2:"do";s:1:"1";s:10:"msgTFormat";s:7:"%TITLE%";s:9:"msgFormat";s:32:"%EXCERPT%
    
    %URL%
    
    
    
    %TAGS%";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doMD";i:0;s:8:"isPosted";s:1:"1";s:4:"pgID";s:12:"b0feaa9e1925";s:7:"postURL";s:103:"https://medium.com/@BitcoinMXN/un-tutorial-muy-b%C3%A1sico-para-instalar-steem-para-python-b0feaa9e1925";s:5:"pDate";s:19:"2018-01-22 09:12:29";}}";
snapPK:
  - 's:296:"a:1:{i:0;a:9:{s:2:"do";s:1:"1";s:9:"msgFormat";s:40:"%TITLE% - %URL% #bitcoin #mexico #crypto";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doPK";i:0;s:8:"isPosted";s:1:"1";s:4:"pgID";i:1366923175;s:7:"postURL";s:30:"https://www.plurk.com/p/mltwo7";s:5:"pDate";s:19:"2018-01-22 09:12:33";}}";'
snapST:
  - |
    s:158:"a:1:{i:0;a:5:{s:2:"do";s:1:"1";s:9:"msgFormat";s:40:"%EXCERPT%
    
    <a href="%URL%">Source</a>";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doST";i:0;}}";
snapSU:
  - |
    s:339:"a:1:{i:0;a:11:{s:2:"do";s:1:"1";s:9:"msgFormat";s:18:"%EXCERPT%
    
    %URL%";s:5:"suCat";s:10:"Technology";s:4:"nsfw";s:1:"0";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doSU";i:0;s:8:"isPosted";s:1:"1";s:4:"pgID";s:6:"1mrJjQ";s:7:"postURL";s:45:"http://www.stumbleupon.com/su/1mrJjQ/comments";s:5:"pDate";s:19:"2018-01-22 09:12:52";}}";
snapTR:
  - |
    s:490:"a:1:{i:0;a:13:{s:2:"do";s:1:"1";s:9:"msgFormat";s:113:"<p>%URL%</p>
    <blockquote><p><strong>%TITLE%</strong></p>
    <p><img src="%IMG%"/></p><p>%EXCERPT%</p></blockquote>";s:8:"postType";s:1:"T";s:10:"msgTFormat";s:7:"%TITLE%";s:9:"isAutoImg";s:1:"A";s:8:"imgToUse";s:0:"";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doTR";i:0;s:8:"isPosted";s:1:"1";s:4:"pgID";i:169994239218;s:7:"postURL";s:46:"http://bitcoinmxn.tumblr.com/post/169994239218";s:5:"pDate";s:19:"2018-01-22 09:12:54";}}";
snapTW:
  - 's:516:"a:1:{i:0;a:12:{s:2:"do";s:1:"1";s:9:"msgFormat";s:149:"(%TITLE%) - %URL% #bitcoin #criptomonedas #criptomoneda #blockchain #bitcoinMexico #bitcoinpanama #bitcoinvenezuela #ethereum #mexico #cryptocurrency";s:8:"attchImg";s:1:"1";s:9:"isAutoImg";s:1:"A";s:8:"imgToUse";s:0:"";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doTW";i:0;s:8:"isPosted";s:1:"1";s:4:"pgID";s:18:"955367665908047872";s:7:"postURL";s:57:"https://twitter.com/mxn_bitcoin/status/955367665908047872";s:5:"pDate";s:19:"2018-01-22 09:12:55";}}";'
snapImportedComments:
  - 'a:0:{}'
categories:
  - Guías
  - STEEM
---
Hoy te mostraré cómo instalar la biblioteca oficial de Steem Python en un sistema operativo basado en Debian o Ubuntu.

También puede ejecutarlo en cualquier sabor de Linux como centOS, fedora, etc. Si no tiene una marca aquí para ejecutarlo como reproductor virtual en la máquina de Windows.

Para Steem Python necesitamos **Python 3.5 o superior,** suerte para nosotros, ubuntu 16.04 ya tiene incorporado Python 3.5.

Al usar el cliente **STEEM Python oficial**, puede hacer cosas increíbles con su cuenta que no se pueden lograr a través de Steemit.com. Por ejemplo, puede aprovechar el poder de Steem, crear nuevas cuentas o crear scripts avanzados.

#### Ahora tenemos que ir a la terminal y escribir los siguientes comandos:

> sudo apt-get update

&nbsp;

#### Instalar la biblioteca ssl:

> sudo apt-get install libssl-dev

### Luego tenemos que instalar pip:

> sudo apt-get install -y python3-pip

##### Es hora de instalar Steem Python, tenga en cuenta que esto debería tomar más de un minuto:

> pip3 install -U steem

##### Ahora que tenemos Steem Python instalado, vamos a importar nuestra cuenta Steemit:

> steempy import

Le pedirá que ingrese su contraseña steemit, luego tendrá que crear una contraseña steempy local, confirmarla y listo, ha importado exitosamente su cuenta steemit.

#### Ahora que ha importado su cuenta, puede hacer muchas cosas divertidas para comenzar con la lista de comandos:

> steempy -h

#### Adelante, juega 🙂
---
id: 125
title: Simplemente descifrando los honorarios de Bitcoin
date: 2017-12-21T01:43:52+00:00
author: Andres
layout: post
guid: http://bitcoinmxn.com/?p=125
permalink: /2017/12/21/simplemente-descifrando-los-honorarios-de-bitcoin/
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
snapST:
  - |
    s:158:"a:1:{i:0;a:5:{s:2:"do";s:1:"1";s:9:"msgFormat";s:40:"%EXCERPT%
    
    <a href="%URL%">Source</a>";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doST";i:0;}}";
snapMD:
  - |
    s:391:"a:1:{i:0;a:10:{s:2:"do";s:1:"1";s:10:"msgTFormat";s:7:"%TITLE%";s:9:"msgFormat";s:32:"%EXCERPT%
    
    %URL%
    
    
    
    %TAGS%";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doMD";i:0;s:8:"isPosted";s:1:"1";s:4:"pgID";s:12:"474b6db96061";s:7:"postURL";s:93:"https://medium.com/@BitcoinMXN/simplemente-descifrando-los-honorarios-de-bitcoin-474b6db96061";s:5:"pDate";s:19:"2017-12-21 01:46:41";}}";
snapPK:
  - 's:296:"a:1:{i:0;a:9:{s:2:"do";s:1:"1";s:9:"msgFormat";s:40:"%TITLE% - %URL% #bitcoin #mexico #crypto";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doPK";i:0;s:8:"isPosted";s:1:"1";s:4:"pgID";i:1364184097;s:7:"postURL";s:30:"https://www.plurk.com/p/mk776p";s:5:"pDate";s:19:"2017-12-21 01:46:45";}}";'
snapSU:
  - |
    s:339:"a:1:{i:0;a:11:{s:2:"do";s:1:"1";s:9:"msgFormat";s:18:"%EXCERPT%
    
    %URL%";s:5:"suCat";s:10:"Technology";s:4:"nsfw";s:1:"0";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doSU";i:0;s:8:"isPosted";s:1:"1";s:4:"pgID";s:6:"1S5URZ";s:7:"postURL";s:45:"http://www.stumbleupon.com/su/1S5URZ/comments";s:5:"pDate";s:19:"2017-12-21 01:47:01";}}";
snapTR:
  - |
    s:490:"a:1:{i:0;a:13:{s:2:"do";s:1:"1";s:9:"msgFormat";s:113:"<p>%URL%</p>
    <blockquote><p><strong>%TITLE%</strong></p>
    <p><img src="%IMG%"/></p><p>%EXCERPT%</p></blockquote>";s:8:"postType";s:1:"T";s:10:"msgTFormat";s:7:"%TITLE%";s:9:"isAutoImg";s:1:"A";s:8:"imgToUse";s:0:"";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doTR";i:0;s:8:"isPosted";s:1:"1";s:4:"pgID";i:168770183783;s:7:"postURL";s:46:"http://bitcoinmxn.tumblr.com/post/168770183783";s:5:"pDate";s:19:"2017-12-21 01:47:03";}}";
snap_isAutoPosted:
  - "1513820823"
snapTW:
  - 's:422:"a:1:{i:0;a:12:{s:2:"do";s:1:"1";s:9:"msgFormat";s:56:"(%TITLE%) - %URL% #bitcoinmxn #espanolbitcoin #bitcoinla";s:8:"attchImg";s:1:"1";s:9:"isAutoImg";s:1:"A";s:8:"imgToUse";s:0:"";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";s:4:"doTW";i:0;s:8:"isPosted";s:1:"1";s:4:"pgID";s:18:"943659050763419649";s:7:"postURL";s:57:"https://twitter.com/mxn_bitcoin/status/943659050763419649";s:5:"pDate";s:19:"2017-12-21 01:47:05";}}";'
dsq_thread_id:
  - "6456495060"
categories:
  - Bitcoin
  - Bitcoin Cash
---
Bitcoin a menudo se promociona como una red de pago global que no incluye tarifas de transacción. Hasta cierto punto, esa afirmación es cierta, pero no cuenta toda la historia. No se aplica ninguna tarifa de transacción para el destinatario en ninguna transacción de bitcoin proveniente de otro usuario de la red. Pero a veces, hay una tarifa de transacción involucrada, aunque muy mínima.

&nbsp;

Las tarifas de transacción en el mundo bitcoin no están incluidas en cada transacción. De hecho, la mayoría de las billeteras de bitcoin permiten al usuario incluir opcionalmente una tarifa de transacción para acelerar la transacción. Al acelerar, se priorizará una transacción que incluya una pequeña tarifa para ser incluida en el siguiente bloque de la red, mientras que las transacciones sin tarifas tienen una prioridad menor.

&nbsp;

Ciertas excepciones a la inclusión de una tarifa de transacción no afectan la velocidad de la transacción. En el cliente Bitcoin Core, si su transacción tiene un tamaño inferior a 1.000 bytes, solo tiene salidas de 0.01 BTC o más, y tiene una prioridad lo suficientemente alta, no se requiere una tarifa de transacción. Todas estas condiciones deben cumplirse para que esta excepción sea aplicable.

&nbsp;

Si no se cumplen estas condiciones, se agregará una tarifa de transacción estándar de 0.0001 BTC por cada mil bytes. Los usuarios clientes de Bitcoin Core notarán cuando una tarifa de transacción es incluida, ya que el cliente solicitará al usuario que acepte o rechace la tarifa asociada con la transacción. Sin embargo, rechazar esa tarifa baja la priorización y afecta la velocidad a la que se aplican las confirmaciones de red.

&nbsp;

La mayoría de las transacciones de bitcoins tienen un tamaño de 500-600 bytes y, dependiendo de la salida, pueden o no estar sujetas a una tarifa de transacción de 0.0001 BTC. Incluir una transacción en un bloque de red es completamente aleatorio, pero se ve afectado por la tarifa de transacción (si es necesario). Cada bloque deja 50,000 bytes de espacio para transacciones de alta prioridad, independientemente de la tarifa de transacción (TX), que se incluirán (aproximadamente 100 transacciones por bloque).

&nbsp;

Después de eso, las transacciones sujetas a la tarifa de 0.00001 BTC / kilobyte se agregan al bloque, con las transacciones de mayor tarifa por kilobyte incluidas primero. Este proceso se repite hasta que el tamaño del bloque alcanza un tamaño de 750,000 bytes.
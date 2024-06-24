Gears
===

Simulador Genérico de Robótica Autônoma Educacional

Este simulador foi criado para permitir que qualquer pessoa experimente robótica sem possuir um robô.

Experimente em [https://gears.aposteriori.com.sg](https://gears.aposteriori.com.sg)

...ou a versão mais recente no GitHub [https://quirkycort.github.io/gears/public/](https://quirkycort.github.io/gears/public/)

Ele usa a API Ev3dev (...e algum suporte inicial para Pybricks), então o código pode ser executado em um Lego Mindstorm EV3 real, se você tiver um.

Instalação
---

O simulador deve ser servido através de um servidor web, e mantemos o site em [https://gears.aposteriori.com.sg](https://gears.aposteriori.com.sg) gratuito para qualquer pessoa usar.

Se você deseja executar sua própria cópia local, faça o download de todos os arquivos e coloque-os em um diretório no seu servidor e isso deve ser suficiente.
Devido à proteção CORS nos navegadores web, ele não funcionará quando servido a partir de uma URL "file://".

Sem um Servidor Web
---

Se você não tem um servidor web, mas tem Python3 instalado em seu computador, você pode tentar...

1. Baixe o Gears de [https://github.com/QuirkyCort/gears/archive/refs/heads/master.zip](https://github.com/QuirkyCort/gears/archive/refs/heads/master.zip)
2. Mude para o diretório "gears/public"
3. Execute `python -m http.server 1337`
Não feche a janela com o comando Python em execução.

Isso deve colocar o site em funcionamento em [http://localhost:1337](http://localhost:1337) (...tente [http://127.0.0.1:1337](http://127.0.0.1:1337) se isso não funcionar).

O site também pode estar disponível para outros usuários na mesma rede usando [http://seu_endereço_IP:1337](http://seu_endereço_IP:1337), onde "seu_endereço_IP" é substituído pelo seu endereço IP real.
Isso pode não funcionar dependendo da configuração da sua rede e das configurações do seu firewall.

Se você não deseja permitir que outros usuários acessem o site, deve executar `python -m http.server 1337 --bind 127.0.0.1` em vez disso.

Créditos
---
Criado por A Posteriori ([https://aposteriori.com.sg](https://aposteriori.com.sg)).

Outros Contribuidores:

Steven Murray
* Arena de Futebol
* ObjectTracker
* Melhorias no ímã
* Atuadores de Rodas

humbug99
* Caneta
* Múltiplas abas de módulos Python

Yuvix25
* Modelos de missões FLL

Este simulador não seria possível sem as grandes pessoas por trás de:

* Babylon.js [https://babylonjs.org](https://babylonjs.org)
* Blockly [https://developers.google.com/blockly](https://developers.google.com/blockly)
* Skulpt [https://skulpt.org](https://skulpt.org)
* Ace [https://ace.c9.io](https://ace.c9.io)
* Ammo.js [https://github.com/kripken/ammo.js/](https://github.com/kripken/ammo.js/) (port do Bullet [https://pybullet.org/](https://pybullet.org/))

Traduções por:

* Français: Sébastien CANET <scanet@libreduc.cc>
* Nederlands: Henry Romkes
* Ελληνικά: Eduact, [https://eduact.org/en](https://eduact.org/en)
* Español: edurobotic
* Deutsch: Annette-Gymnasiums-Team (Johanna, Jule, Felix), germanicianus
* Português: Mateus Lima
* עברית: Koby Fruchtnis

Licença
---
Licença Pública Geral GNU v3.0

O seguinte software de código aberto está incluído aqui para conveniência.
Por favor, consulte os respectivos sites para informações sobre licenças.

* Babylon.js
* Blockly
* Ace Editor
* Skulpt
* Ammo.js
* Cannon.js
* Oimo.js
* Pep
* Jquery
* JSZip
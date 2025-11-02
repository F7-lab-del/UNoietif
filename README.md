# UNoietif
===============================================
|     | |\      |  _____  .  ____ ____ .  ____
|     | |  \    | |     | | |      |   | |
|     | |    \  | |     | | |____  |   | |____
|_____| |      \| |_____| | |____  |   | | 
===============================================
Desenvolvido por: F7

Descrição: UNoietif é uma ferramenta de extenssão .bat projetado para parar/neutralizar um dos, se não, o malware mais destruidor de todos os tempos o oietif, um virús extremamente perigoso que consegue, usando permissões de baixo nível, apagar o CMOS, sobrescrever a UEFI/BIOS, sobrescrever o HD e modificar a MBR para uma mensagem ecrita: "you just got OIETIFed. Game over". Tudo isso de forma quase instantanea, ou seja,se esse .bat for executado, após 2 a 4 segundos, o computador crasha e apaga o Windows e aparece uma MBR diferente, e após isso a maquina acaba ficando inoperante devido aos danos causados aos componentes de hardware citados anteriormente, por isso, que na opinião do autor do UNoietif ele é o mais destrutivo de todos os tempo, porque além disso, este malware não possui nenhuma ferramenta de combate conhecida, foi aí que o autor, após muitos estudos do codigo fonte desse malware desenvolver uma ferramenta .bat que pudesse parar instantaneamente o virús e garantir que a máquina não se torne inoperante.

O que ele faz: Ao executar o .bat, ele cria um script de monitoramento "wscript.exe" que por sua vez, roda em segundo plano na maquina do usuário, que oferece proteção em dupla camada, ele monitora monitora a pasta %appdata% local esse que o malware atua, dropando 2 arquivos o "x.js" e o "s.exe" que são responsaveis pela destruição da maquina, o .bat foi projetado para apagar-los rapidamente através de um loop 100 milisegundos, fazendo com que o arquivo mal-intencionado não consiga usar o x.js para decodificar o s.exe que é o executavel que destroi a máquina. E ao apagar ele exibe uma rapida mensagem escrita: "you were not OIETIFed. Continue the game and relax" uma forma de referência a MBR modificada do oietif, logo após a caixa de mensagem, o computador permanece operante e sem danos.

IMPORTANTE!: se você quiser testar esta ferramenta contra o virus real, execute ele primeiro!

- Se você fez o dowload, te agradeço pela sua colaboração. ;)


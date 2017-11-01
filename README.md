C# Configurar VPS SSH/SQUID3 & MANAGER [ EDITADO ] 
                                                            SCRIP ORIGINAL 
                                                     https://github.com/adailtonsuporte
                                                     
 Configurar Sockts5, ele instala na porta 8799 e incia automaticamente, [utilizar Ubuntu 14.04]
 > apt-get update && wget https://raw.githubusercontent.com/Morfeu013/ShadowSockts5/master/proxy.py && screen -d -m -t socks python proxy.py
 
 
 # Logo após continue com a instalação do ShadowManager

<body>
  <tr>
    <td width="100px" class="main2"><b></b></td><td width="780px"></td>
  </tr>
   <tr>
    <td width="100px" class="main2"><b></b></td><td width="780px"></td>
  </tr>
<table border="0" cellpadding="0" cellspacing="2" width="100%">
  <tr>
    <td width="100px" class="main2"><b>Ferramenta:</b></td>
    <td width="780px" class="main2"><b>ShadowManager V2.0</b></td>
  <tr>
    <td width="100px" class="main2"><b>Author:</b></td><td width="780px">Zwdeff feat. Júnior Soares</td>
  </tr>
  <tr>
    <td width="100px" class="main2"><b>Versão:</b></td><td width="780px">2.0</td>
  </tr>
  <tr>
    <td width="100px" class="main2"><b>Termo:</b></td><td width="780px">Eu fiz este script sem nenhuma intenção maliciosa ... Podem usar sem medo, mais não asumirei nenhuma responsabilidade por usarem meu scripts alterado por terceiros .. Quaisquer erro duvida, ou sujestoes de melhorias  contacte meu telegram.</td>
  </tr>
  <tr>
    <td width="100px" class="main2"><b>Novidades v2.0</b></td><td width="780px">Melhorias no Codigo
    </td>
  </tr>
  <tr>
    <td width="100px" class="main2"><b>Canal do Telegram:</b></td><td width="780px">https://telegram.me/vpspaga</td>
  </tr>
  <tr>
    <td width="100px" class="main2"><b>Privado:</b></td><td width="780px">@eujrsoares</td>
  </tr>
<table border="0" cellpadding="2" cellspacing="5" width="100%">
  <tr>
    <td width="100px" class="main2">&#9733;<b>Descrição:</b></td><td width="780px">ShadowManager é um script em python3 que ao configurar uma vps, ele detecta se a pasta do squid é squid ou squid3, configurando(a) assim qualquer vps. para editrar o arquivo /ssh/sshd_config ele substitue no meio do arquivo Port 22 por Port 22,443 deixando o arquivo sshd intacto, ao contrario de outros scripts em shell, que alterão todo o arquivo para alterar um simples texto, é outros que escrevem Port 443 no final do arquivo ocasionando erros em sua VPS.</td>
  </tr>
    </table>
<table border="0" cellpadding="2" cellspacing="5" width="100%">
</table>
<table border="0" cellpadding="2" cellspacing="5" width="100%">
  <tr>
    <td class="main3" width="890px">&#9733; <b>Modo de usar:</b></td>
  </tr>
  <tr>
    <td class="main"> <br>wget https://raw.githubusercontent.com/Morfeu013/ShadowManager/master/.config.py<br/> <br>chmod +x .config.py<br/> <br>python3 .config.py<br/> <b> Caso o python3 não estiver instalado : apt-get install python3</td>
  </tr>
</body>
</html>

# EPG para televisão portuguesa

Exemplo de utilização:
```
# exemplo de canal no ficheiro .xml

  <channel id="RTP 1">
    <display-name lang="pt">RTP 1 HD</display-name>
    <url>http://www.nos.pt</url>
  </channel>
```

Utilizando um exemplo de lista IPTV, basta que no campo "tvg-id" ou o campo do nome do canal seja igual ao "channel id", para que a grelha apareça corretamente para um determinado canal.

```
#EXTM3U
#EXTINF:-1 tvg-id="RTP 1",NOME DO CANAL QUE QUISEREM
http://null
```

# Fontes Utilizadas

  * https://mag.sapo.pt/tv/programacao
  * https://nos.pt/particulares/televisao/guia-tv/Pages/default.aspx
  * https://tvnetvoz.vodafone.pt/sempre-consigo/guia-tv
  * https://www.elevensports.pt/channel/elevensports1

# Utilização
O link a colocar na parte de epg pode ser o seguinte: http://bit.ly/epg-pt

Qualquer dúvida ou canais que queiram adicionados/removidos, façam pedido!

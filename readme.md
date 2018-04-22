## YouTube vídeo downloader v0.9
### Este código permite o download de vídeos do youtube

A aplicação usa somente javascript e html, o que permite a execução do código diretamente no navegador sem a necessidade de um servidor web.

A compatibilidade deste código é limitada aos navegadores:
>*Chrome >= 29.0*
>*Firefox >= 44.0*

Não foi testado em outros navegadores.

## Problemas da versão 0.9
O código não está 100% funcional

>Os botões de download não executam o download diretamente, mas redirecionam para o link direto do vídeo. Dessa forma é possível executar o download via gerenciador externo.

>Existem problemas de compatibilidade com navegadores devido ao uso de uma função(URLSearchParams) com suporte fraco entre os motores web.

>Devido a um problema de cors, foi necessário o uso de um proxy para burlar essa limitação. O proxy https://cors.io/ está sendo usado. Sendo assim se este proxy parar de funcionar a aplicação não funcionará mais.

>O código não foi testado com grande variedade de links, o que pode significar a existência de bugs desconhecidos.
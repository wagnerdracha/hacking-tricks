Web

- https://echo.opera.com/
	- Obtém informações sobre o request

- Qual navegador está usando
	- Muitas vezes, o USER-AGENT pode ser modificado. Dessa maneira, pode-se verificar também o tipo do navegador pela posição dos cabeçalhos no request.
por exemplo:
	- Firefox 112..0.2 (64-bits) tem a ordem de cabeçalho:
Host:	echo.opera.com
User-Agent:	Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/112.0
Accept:	text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language:	pt-BR,pt;q=0.8,en-US;q=0.5,en;q=0.3
Accept-Encoding:	gzip, deflate, br
Connection:	keep-alive
Upgrade-Insecure-Requests:	1
Sec-Fetch-Dest:	document
Sec-Fetch-Mode:	navigate
Sec-Fetch-Site:	none
Sec-Fetch-User:	?1

	- Firefox 40.0 tem a seguinte ordem:
Host:	echo.opera.com
User-Agent:	Mozilla/5.0 (Windows NT 10.0; WOW64; rv:40.0) Gecko/20100101 Firefox/40.0
Accept:	text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language:	en-US,en;q=0.5
Accept-Encoding:	gzip, deflate
Connection:	keep-alive

	- Chrome 107.0.5304.104 (64 bits) tem a seguinte ordem:
Host:	echo.opera.com
Sec-Ch-Ua:	"Google Chrome";v="107", "Chromium";v="107", "Not=A?Brand";v="24"
Sec-Ch-Ua-Mobile:	?0
Sec-Ch-Ua-Platform:	"Windows"
Upgrade-Insecure-Requests:	1
User-Agent:	Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/107.0.0.0 Safari/537.36
Accept:	text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
Sec-Fetch-Site:	none
Sec-Fetch-Mode:	navigate
Sec-Fetch-User:	?1
Sec-Fetch-Dest:	document
Accept-Encoding:	gzip, deflate
Accept-Language:	pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7
Connection:	close

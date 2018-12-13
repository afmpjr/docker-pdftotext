#### A imagem comprimida tem apenas 7MB

[Alpine](https://alpinelinux.org/) com [Poppler](https://poppler.freedesktop.org/) Utils (pdftotext)

Para processar o arquivo PDF, use esse comando:
```
docker run -v <CAMINHO_DA_PASTA_LOCAL>:<CAMINHO_DA_PASTA_NO_CONTAINER> juniormendonca/alpine-poppler-utils pdftotext -layout <CAMINHO_DA_PASTA_NO_CONTAINER>/documento.pdf <CAMINHO_DA_PASTA_NO_CONTAINER>/documento.txt
```

> Meu hub [https://hub.docker.com/u/juniormendonca/](https://hub.docker.com/u/juniormendonca/)

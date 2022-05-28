### Docker -NGINX

* image: nginx:1.17.6-alpine


#### Up
```
docker-compose up -d
```

#### Add bash

```
docker-compose exec nginx apk add bash
```

#### Access contaneir

```
docker-compose exec nginx bash
```

#### Command apk
```
apk add vim
```
*Opção*

* add = novo pacote;
* del = remove pacote;
* update = atualiza reposetório;
* info = ver informações do pacote;
* list = lista de pacotes( ou mostrar pacotes instalados)

**pacote = programa no mundo Windows;


#### Nginx

Arquivo de configuração padrão
> /etc/nginx/nginx.conf

Diretório de configuração, *.conf
> /etc/nginx/conf.d/

Arquivo padrão HTML
> /usr/share/nginx/html/index.html


Validar alterações
```
nginx -t
```


#### funçẽos

proyx_pass http://coloqueAquiHost # Proxy Reverso;





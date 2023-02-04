# nginx-reverse_proxy-load_balancer

Para que o teste funcione corretamente, é necessário uma alteração na pasta "hosts" da maquina, no modo de administrador.

Linux: `/etc/hosts`.
windows: `c:/Windows/System32/drivers/etc/hosts`.

Adicinar o seguinte:

```
127.0.0.1 test.com.br
127.0.0.1 blue.test.com.br
```

Dessa forma será possivel acessar o nginx pelo navegador, e ser redirecionado através do ServerName.
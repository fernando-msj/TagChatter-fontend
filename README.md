# Implementação do Front-end TagChatter

Apenas tenha certeza de estar em um navegador moderno com suporte a javascript ES6 e ir no link:

https://cold-meson-06.github.io/TagChatter

E é só isso, brincadeira né. Você tambem tem que..., não é só isso mesmo.

Caso não funcione pode ser que o servidor tenha fechado, então você pode clonar o repositorio, e se tiver node hospedar um servidor http na localhost:

```
http-server -p8080 -o
```

Caso não tenha o módulo pode encontrá-lo [neste link](https://www.npmjs.com/package/http-server). 

Mas ainda não temos o server, para resolver este problema você pode ir no [index.html](https://github.com/Cold-Meson-06/TagChatter-fontend/blob/master/index.html#L85) e ativar o modo de teste:

```html
<script>TESTING_ENABLED=false</script>
```

E você terá uma simulação do servidor rodando. 
A simulação *não* implementa os requisitos do projeto como atualização a cada 3 segundos e falha intencional de 25% de chance, a própia simulção não está nos requisitos. Porêm seria trivial adicionar tal funcionalidade.

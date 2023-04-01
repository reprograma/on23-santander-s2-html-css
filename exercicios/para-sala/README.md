# Exercício de Sala 🏫  

## HTML DO ZERO!

- Explicação do exercício: Teremos varios pequenos exercicios em sala, mas a ideia é trabalharmos em pequenos passos. 
---
Iniciaremos mexendo e entendendo a estrutura de um site HTML:


```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Minha página web</title>
  </head>
  <body>
    <h1>Aqui vai um título</h1>

    <p>Aqui vai um texto, um longo texto, exibido como um parágrafo.</p>

    <a href="www.reprograma.com">Visite a página da reprograma clicando aqui!</a>
  </body>
</html>

```

Depois passaremos por um site com HTML semântico:

```
<!DOCTYPE html>
<html>
 <head>
   <meta charset="utf-8">
   <title>Minha página web</title>
 </head>
 <body>
   <header>
     <h1>Aqui vai um título</h1>
   </header>
   <main>
     <section>
       <p>Aqui vai um texto, um longo texto, exibido como um parágrafo.</p>

       <a href="www.reprograma.com">Visite a página da reprograma clicando aqui!</a>
     </section>
   </main>

   <footer>
     Copyright Thiele
   </footer>
 </body>
</html>

```


Tambem vamos construir um forms:

```
<form action="/login" method="POST">
    <p>
        <label>Nome:</label>
        <input type="text" name="usuario">
    </p>
    <p>
        <label>Email:</label>
        <input type="email" name="email">
    </p>
    <p>
       <button type="submit">Enviar</button>
    </p>
</form>
```

Terminou o exercício? Dá uma olhada nessa checklist e confere se tá tudo certinho, combinado?!

- [ ] Acompanhei os exercícios  em aula
- [ ] Fiz alterações na versão final do projeto
- [ ] Adicionei as mudanças. (`git add .` para adicionar todos os arquivos, ou `git add nome_do_arquivo` para adicionar um arquivo específico)
- [ ] Commitei a cada mudança significativa ou na finalização do exercício (`git commit -m "Mensagem do commit"`)
- [ ] Pushei os commits na minha branch (`git push origin nome-da-branch`)

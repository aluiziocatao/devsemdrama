# </> DevSemDrama · Exercícios

**Assistiu o vídeo? Agora testa.**

Exercícios rápidos de lógica de programação, um para cada vídeo do [DevSemDrama no TikTok](https://www.tiktok.com/@devsemdrama). Sem cadastro, sem instalar nada, direto do celular.

👉 **Acesse:** https://SEU-USUARIO.github.io/devsemdrama

---

## Exercícios disponíveis

| # | Tema | O que você pratica |
|---|------|--------------------|
| 01 | Copiar código não é aprender | Ler e explicar um código antes de usar |
| 02 | Linguagem não importa | A mesma lógica em JavaScript, Python e Java |
| 03 | IA vai acabar com dev? | Revisar código e achar o bug que a IA deixou passar |
| 04 | Erro não é fracasso | Ler mensagens de erro e encontrar a causa |
| 05 | Por onde começar | A ordem certa para aprender programação |
| 06 | Lógica em 30 segundos | Decisão (`if`) e repetição (`for` / `while`) |
| 07 | Variável explicada pra criança | Como variáveis guardam e trocam valores |
| 08 | IF sem dor | Condições e a diferença entre `>` e `>=` |

Cada exercício tem um link direto. Por exemplo, `.../devsemdrama/#05` abre o exercício do vídeo 05.

## Como funciona

- Cada vídeo tem de 3 a 4 perguntas de múltipla escolha.
- Ao responder, aparece a explicação, mostrando por que a resposta certa é a certa.
- No fim tem um **desafio extra** para tentar sozinho antes de ver a resposta.
- O progresso fica salvo no seu navegador. Nada é enviado para servidor nenhum.

## Rodar localmente

É um único arquivo HTML, sem dependências. Baixe o `index.html` e abra no navegador.

## Adicionar um novo exercício

No começo do `<script>` do `index.html` existe a lista `AULAS`, com um bloco por vídeo:

```js
{n:'09', t:'Título do vídeo', d:'Subtítulo curto',
 q:[
   {p:'Pergunta', code:'código opcional',
    o:['Alternativa A','Alternativa B','Alternativa C'], c:1,
    e:'Explicação que aparece depois da resposta.'}
 ],
 x:{p:'Desafio extra', code:'código opcional', r:'Resposta do desafio'}},
```

- `c` é o índice da alternativa correta, começando em 0.
- `code` é opcional e aparece com realce de sintaxe.

Copie um bloco, troque o número e o conteúdo, e faça o commit. O GitHub Pages publica sozinho.

---

Feito por **DevSemDrama**: programação sem drama, sem promessa milagrosa, só lógica e prática.
Me segue no TikTok: [@devsemdrama](https://www.tiktok.com/@devsemdrama)

# Amigo Secreto 🎁

Este projeto é um site simples para sortear amigos no Amigo Secreto. Ele permite que os usuários adicionem nomes a uma lista e realizem um sorteio aleatório. Desenvolvido como desafio do curso Alura Praticando lógica de programação.

## 🚀 Funcionalidades
- Adicionar nomes à lista.
- Validar entradas (não permite nomes vazios).
- Exibir a lista de amigos adicionados.
- Sortear aleatoriamente um amigo da lista.
- Exibir o amigo sorteado na tela.

## 📂 Estrutura do Projeto
```
/
├── index.html      # Estrutura do site
├── style.css       # Estilos do site
├── app.js          # Lógica do sorteio
└── assets/         # Imagens e ícones
```

## 🛠 Tecnologias Utilizadas
- **HTML** para a estrutura do site.
- **CSS** para estilização.
- **JavaScript** para a lógica de sorteio e manipulação do DOM.

## 🎯 Como Usar
1. Clone ou baixe o repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Digite o nome dos participantes e clique em "Adicionar".
4. Após adicionar todos os participantes, clique em "Sortear amigo".
5. O nome sorteado será exibido na tela.

## 📌 Implementação
- A lista de amigos é armazenada em um array `amigos`.
- Os nomes são adicionados à lista com `push()` e exibidos dinamicamente no DOM.
- O sorteio é feito com `Math.random()` e `Math.floor()`.
- `innerHTML` é utilizado para atualizar a exibição na tela.

## 📜 Licença
Este projeto é de código aberto e pode ser usado livremente.


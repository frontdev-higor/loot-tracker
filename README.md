# ⚔️ Raid Loot Tracker

Ferramenta para rastrear a distribuição de loot (itens) entre jogadores durante raids no **World of Warcraft: Wrath of the Lich King** (servidor Warmane - Onyxia).

Criado por **Alanya** da guilda **Lagados e Furiosos** (Horda) e para uso dos jogadores de World of Warcraft no geral.

## Funcionalidades

- **Adicionar/remover jogadores** — Monta a lista da raid em tempo real
- **Contador de loot individual** — Cada jogador tem botões +/- para registrar quantos itens recebeu
- **Classe do WoW** — Clique no emblema para selecionar a classe do jogador (Death Knight, Druid, Hunter, Mage, Paladin, Priest, Rogue, Shaman, Warlock, Warrior), com cores e emojis oficiais
- **Modo Horda / Aliança** — Alterna entre tema escuro (Horda) e tema claro (Aliança)
- **Contador de jogadores** — Mostra quantos jogadores estão na raid
- **Resetar raid** — Limpa toda a lista de uma vez
- **Dados salvos** — Os jogadores, classes e contagem de loot ficam salvos no navegador (localStorage), então a página pode ser fechada sem perder os dados

## Como usar

1. Abra o arquivo `index.html` no navegador
2. Digite o nome do jogador e clique em **Adicionar**
3. Clique no emblema (**?**) para selecionar a classe do jogador
4. Use os botões **+** e **-** para contar os itens recebidos
5. Os dados são salvos automaticamente

## Tecnologias

- HTML5
- CSS3
- JavaScript (sem frameworks)

## Conceitos de JavaScript aplicados

- Manipulação do DOM (`querySelector`, `createElement`, `appendChild`)
- Eventos (`addEventListener`, `click`)
- Estado com variáveis (`let`, closure)
- Arrays e objetos
- `classList` (add, remove, toggle, contains)
- Spread operator (`...classes`)
- `Array.from()` e `forEach`
- `localStorage` com `JSON.stringify` / `JSON.parse`
- `.find()` e `.indexOf()` para busca em arrays
- Template literals

---

Desenvolvido por **Elias Higor**

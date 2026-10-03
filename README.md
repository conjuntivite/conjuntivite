<div align="center">

<img src="assets/hero.svg" alt="conjuntivite — Desenvolvedor Full-Stack, segurança eletrônica e CFTV" width="100%">

<a href="https://github.com/conjuntivite/SPECIUM"><b>SPECIUM</b></a> &nbsp;·&nbsp;
<a href="https://github.com/conjuntivite/WCOEN"><b>WCOEN</b></a> &nbsp;·&nbsp;
<a href="https://github.com/conjuntivite/BUSCADOR-V1"><b>BUSCADOR</b></a>


[![GitHub followers](https://img.shields.io/github/followers/conjuntivite?label=Seguidores&style=social)](https://github.com/conjuntivite)
![Visitantes](https://visitor-badge.laobi.icu/badge?page_id=conjuntivite.conjuntivite)


</div>

Desenvolvedor full-stack com foco em **soluções pra segurança eletrônica e CFTV** — do
levantamento técnico à automação de orçamento e instalação. Gosto de construir ferramentas que
resolvem um problema real do dia a dia, não só código bonito no vácuo.


<img src="assets/sec-sobre.svg" alt="Sobre mim" width="100%">

```javascript
const conjuntivite = {
  papel: "Desenvolvedor Full-Stack",
  foco: ["segurança eletrônica", "CFTV", "automação de orçamento", "IA aplicada"],
  construindoAgora: ["SPECIUM — Intelligent System Design", "WCOEN — balancete pessoal pelo WhatsApp"],
  stack: {
    frontend: ["React 19", "Vite", "Tailwind CSS", "shadcn/ui", "React Flow"],
    backend: ["Node.js (puro, sem framework)", "TypeScript", "MongoDB", "PostgreSQL", "Docker", "Baileys (WhatsApp)"],
    mapas: ["Leaflet", "MapLibre", "OpenStreetMap"],
    ia: ["OpenRouter (DeepSeek V4 Flash)", "Claude Code"],
  },
  filosofia: "ferramenta que resolve problema real > código bonito no vácuo",
};
```


<img src="assets/sec-stack.svg" alt="Stack" width="100%">

<div align="center">

**Front-end**<br>
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radixui&logoColor=white)

**Back-end**<br>
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_(Baileys)-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

**Mapas**<br>
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)
![MapLibre](https://img.shields.io/badge/MapLibre-396CB2?style=for-the-badge&logo=maplibre&logoColor=white)
![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=for-the-badge&logo=openstreetmap&logoColor=white)

**IA e ferramentas**<br>
![OpenRouter](https://img.shields.io/badge/OpenRouter-94A3B8?style=for-the-badge&logo=openrouter&logoColor=black)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>


<img src="assets/sec-destaque.svg" alt="Projeto em destaque" width="100%">

<a href="https://github.com/conjuntivite/SPECIUM"><img src="assets/card-specium.svg" alt="SPECIUM — Intelligent System Design, orçamento de CFTV e segurança eletrônica" width="100%"></a>

<table>
<tr>
<td width="50%"><img src="assets/specium-login.png" alt="Tela de login do SPECIUM com o radar de equipamentos: câmera IP, NVR, switch PoE, nobreak e leitor facial" width="100%"></td>
<td width="50%"><img src="assets/specium-canvas.jpg" alt="Canvas do SPECIUM com rack, câmeras IP e fontes ligados por cabo de rede" width="100%"></td>
</tr>
<tr>
<td align="center"><sub>Login: Projete. Valide. Instale.</sub></td>
<td align="center"><sub>Canvas do orçamento: rack, câmeras e fontes ligados por tipo de cabo</sub></td>
</tr>
</table>

Sistema completo pra orçamento de instalação de CFTV e segurança eletrônica — o comercial monta o
projeto num canvas e o sistema aponta o que falta pra instalação funcionar de verdade.

| | |
|---|---|
| 🧩 **Canvas de orçamento** | Quadro visual com React Flow, containers (rack com equipamentos dentro) e ligações por tipo de cabo (rede, CCI, coaxial, dupla capa, paralelo) |
| 💡 **Motor de sugestões** | Recalcula a cada item o que falta (switch PoE, cabo, fonte, gravação), separando essencial de recomendado |
| 🤖 **Validação de PDF com IA** | Lê um orçamento pronto em PDF, classifica os itens em lotes e aponta erros e faltas (DeepSeek via OpenRouter). Uma **memória de classificação** no banco reaproveita respostas anteriores: orçamento com itens já conhecidos nem chama a IA |
| 🗺️ **Mapa e planta baixa** | Posiciona câmeras no endereço real ou na planta, com área de cobertura por resolução (IEC 62676-4) |
| 📦 **Catálogo** | +450 produtos em +140 categorias, com ficha técnica e comparação lado a lado; exporta e importa para um arquivo versionado no Git |
| 📑 **Fichas de datasheets oficiais** | Intelbras, Hikvision, ONE e SIAM validados no datasheet do fabricante (alimentação, PoE, zonas, compatibilidade entre linhas) — a IA consulta só a ficha do modelo citado |
| 🛎️ **Assistente de projeto** | Monta o projeto a partir de regras fixas dos fabricantes (SIAM/ONE: facial por marca, antena veicular na rede, 1 acesso por controladora, sensores e barreiras) e importa direto pro canvas |
| 🔐 **Acesso** | Etapas do orçamento (aberto → negociação → fechado) e permissão por tela, editável pelo admin, que também cadastra usuários pela tela |


<img src="assets/sec-outros.svg" alt="Outros projetos" width="100%">

<a href="https://github.com/conjuntivite/WCOEN"><img src="assets/card-wcoen.svg" alt="WCOEN — balancete pessoal pelo WhatsApp" width="100%"></a>

<table>
<tr>
<td width="50%"><img src="assets/wcoen-entrar.png" alt="Tela de entrada do WCOEN com a prévia da mensagem do bot" width="100%"></td>
<td width="50%"><img src="assets/wcoen-dashboard.png" alt="Dashboard do WCOEN com saldo, receitas, despesas e gráfico dos últimos 6 meses" width="100%"></td>
</tr>
<tr>
<td align="center"><sub>Entrada do portal, com a prévia do balancete que o bot envia</sub></td>
<td align="center"><sub>Dashboard: saldo do mês, últimos 6 meses e despesas por categoria (dados de exemplo)</sub></td>
</tr>
</table>

Um bot de WhatsApp que registra despesas e receitas digitadas num grupo (`mercado 45,90`,
`+ 70 plantão`), guarda tudo no PostgreSQL (Docker ou Supabase) e responde com balancetes, extrato e
uma auditoria com IA. Agora também com **portal web multiusuário** (contas por convite, login,
redefinição de senha por e-mail e administração de contas), pronto pra subir no Render. Feito com
TypeScript e testado (Vitest), sem usar a API oficial (paga) do WhatsApp.

| | |
|---|---|
| 💬 **Lançamento por texto livre** | Entende valor antes ou depois da descrição, sinais `+`/`-`, datas como `ontem` ou `15/09` e palavras de receita (salário, plantão, venda) |
| 📊 **Relatórios** | Balancete do dia, resumos mensal, semanal e anual, e extrato paginado do mais recente ao mais antigo |
| 🔎 **Auditoria com IA** | Ranking dos maiores gastos e comparação com o período anterior calculados em código; a IA (OpenRouter) só escreve as dicas |
| 👥 **Contas e portal web** | Cada pessoa com a sua conta: cadastro por convite, redefinição de senha de uso único (validade de 1 h) e tela de administração |
| 🛡️ **Confiabilidade** | Só confirma depois de gravar, recupera mensagens enviadas com o bot offline, reconecta sozinho e nunca manda dados a modelo gratuito |

<a href="https://github.com/conjuntivite/BUSCADOR-V1"><img src="assets/card-buscador.svg" alt="BUSCADOR-V1 — comparador de preços de hardware" width="100%"></a>

Você informa a peça (categoria, marca e modelo) e o servidor busca ofertas em várias lojas, descarta
o que não é o produto exato e devolve tudo ordenado por preço em reais. Servidor em Node.js puro (sem
framework), front-end estático em JS vanilla e testes com o runner nativo do Node (`node --test`).

| | |
|---|---|
| 🛒 **Vários provedores** | KaBuM! (lê o JSON da própria página, sem chave), Amazon (Chrome headless com Puppeteer) e Google Shopping via Serper e SerpApi (pagos, opcionais) |
| 🎯 **Oferta exata** | Normaliza os títulos e filtra o que não bate com o modelo pedido, em vez de listar tudo que aparece na busca |
| ⚖️ **Comparação de ficha técnica** | Compara 2 ou 3 ofertas: CPU, GPU e disco com benchmark do PassMark (cache de 24 h); RAM, placa-mãe e fonte lidas do título |
| 🚧 **Sem burlar proteção anti-bot** | Lojas com bloqueio (Terabyte, Pichau, Mercado Livre, Magalu) foram avaliadas e deliberadamente ficaram de fora |


<img src="assets/sec-stats.svg" alt="Estatísticas" width="100%">

<div align="center">

![Streak stats](https://github-readme-streak-stats.herokuapp.com/?user=conjuntivite&theme=tokyonight&hide_border=true)

</div>

<details>
<summary>🏆 Troféus</summary>
<br>

![Troféus](https://github-profile-trophy.vercel.app/?username=conjuntivite&theme=tokyonight&no-frame=true&row=1&column=7)

</details>


<img src="assets/sec-waka.svg" alt="Tempo de código (WakaTime)" width="100%">

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-47%20hrs%2048%20mins-blue?style=flat)

![AI Code Time](http://img.shields.io/badge/AI%20Code%20Time-48%20hrs%2032%20mins-blue?style=flat)

![Profile Views](http://img.shields.io/badge/Visualizac%C3%B5es%20do%20perfil-22-blue?style=flat)

**🐱 Meus dados no GitHub** 

> 📦 4.3 kB Usado no armazenamento do GitHub 
 > 
> 🏆 287 Contribuições no ano de 2026
 > 
> 🚫 Não aberto para contratação
 > 
> 📜 6 Repositórios Públicos 
 > 
> 🔑 0 Repositórios Privados 
 > 
**Eu sou diurno 🐤** 

```text
🌞 Manhã                  309 commits         █████░░░░░░░░░░░░░░░░░░░░   21.12 % 
🌆 Tarde                  546 commits         █████████░░░░░░░░░░░░░░░░   37.32 % 
🌃 Noite                  428 commits         ███████░░░░░░░░░░░░░░░░░░   29.25 % 
🌙 Madrugada              180 commits         ███░░░░░░░░░░░░░░░░░░░░░░   12.30 % 
```
📅 **Sou mais produtivo em Segunda-Feira** 

```text
Segunda-Feira            409 commits         ███████░░░░░░░░░░░░░░░░░░   27.96 % 
Terça-Feira              121 commits         ██░░░░░░░░░░░░░░░░░░░░░░░   08.27 % 
Quarta-Feira             89 commits          ██░░░░░░░░░░░░░░░░░░░░░░░   06.08 % 
Quinta-Feira             108 commits         ██░░░░░░░░░░░░░░░░░░░░░░░   07.38 % 
Sexta-Feira              373 commits         ██████░░░░░░░░░░░░░░░░░░░   25.50 % 
Sábado                   349 commits         ██████░░░░░░░░░░░░░░░░░░░   23.86 % 
Domingo                  14 commits          ░░░░░░░░░░░░░░░░░░░░░░░░░   00.96 % 
```


📊 **Esta semana eu gastei meu tempo em** 

```text
🕑︎ Fuso horário: America/Sao_Paulo

💬 Linguagens de programação: 
Nenhuma atividade rastreada esta semana

🔥 Editores: 
Nenhuma atividade rastreada esta semana

🐱‍💻 Projetos: 
Nenhuma atividade rastreada esta semana

💻 Sistema operacional: 
Nenhuma atividade rastreada esta semana
```

🤖 **AI Coding This Week** 

```text
No AI Coding Activity Tracked This Week
```

**Eu geralmente programo em JavaScript** 

```text
JavaScript               2 repos             ████████████░░░░░░░░░░░░░   50.00 % 
Python                   1 repo              ██████░░░░░░░░░░░░░░░░░░░   25.00 % 
TypeScript               1 repo              ██████░░░░░░░░░░░░░░░░░░░   25.00 % 
```



**Linha do tempo**

![Lines of Code chart](https://raw.githubusercontent.com/conjuntivite/conjuntivite/main/assets/bar_graph.png)


 Last Updated on 03/10/2026 03:54:47 UTC
<!--END_SECTION:waka-->


<img src="assets/sec-snake.svg" alt="Atividade recente" width="100%">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/conjuntivite/conjuntivite/output/github-contribution-grid-snake-dark.svg">
  <img alt="Snake animation" src="https://raw.githubusercontent.com/conjuntivite/conjuntivite/output/github-contribution-grid-snake.svg">
</picture>


<img src="assets/sec-contato.svg" alt="Contato" width="100%">

[![E-mail](https://img.shields.io/badge/tawan.barbosa@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tawan.barbosa@gmail.com)

# 🌿 ecomoda-instituto

Site institucional e vitrine online do **Instituto EcoModa**, ONG e marca de moda sustentável que faz upcycling de tecidos e emprega mulheres em situação de vulnerabilidade social.

🔗 **Site publicado:** `https://SEU-USUARIO.github.io/ecomoda-instituto/`

## 1. Briefing do problema

O Instituto EcoModa, gerido por Sofia Andrade, vende em feiras e no show-room da sede, e a história de cada peça contada boca a boca sempre funcionou bem. Agora a produção cresceu e a ONG precisa alcançar o Brasil todo para pagar dignamente as 10 artesãs.

**Dores:**
- Vendas por Instagram e mensagens privadas consomem horas da equipe (disponibilidade de peças únicas, frete manual, envio de dados do PIX).
- Sem vitrine organizada, compradores desistem no meio da conversa.
- Concorrência de grandes marcas de fast-fashion com coleções "verdes" (greenwashing).

**Oportunidade:** transparência. Mostrar quem produziu cada peça e o impacto ecológico da compra.

## 2. Solução escolhida: site institucional com vitrine

Optei por um **site estático (HTML + CSS)** porque:

| Motivo | Explicação |
|---|---|
| Resolve a dor principal | Uma vitrine pública substitui as perguntas repetidas de "tem disponível?" e "quanto é?" |
| Diferencial competitivo | Cada produto exibe a artesã responsável e o impacto ecológico (rastreabilidade) |
| Baixo custo | Hospedagem gratuita (GitHub Pages) e nenhuma manutenção de servidor, ideal para uma ONG |
| Simples de manter | A equipe administrativa consegue atualizar o conteúdo com pouco esforço |

Um app móvel ou um sistema completo seriam mais caros e mais lentos de entregar. O site é o primeiro passo ideal, e pode evoluir depois.

## 3. Telas / Protótipo

| Seção | Objetivo |
|---|---|
| **Início** | Proposta de valor e botão para a vitrine |
| **Como funciona** | Escolha → Pague → Acompanhe |
| **Vitrine** | Cards de peças únicas com preço, artesã e impacto |
| **Nossas artesãs** | Humaniza a marca |
| **Contato / Pedido** | Formulário com nome, CEP e peça desejada |

> 📸 Adicione aqui prints do site em `docs/` (ex.: `![Home](docs/home.png)`).

## 4. Arquitetura

Site estático, sem back-end e sem banco de dados.

```
ecomoda-instituto/
├── index.html      # estrutura e conteúdo
├── css/
│   └── style.css   # estilos e responsividade
├── .gitignore
├── LICENSE
└── README.md
```

- **HTML5 semântico** (`header`, `main`, `section`, `footer`)
- **CSS3** com variáveis, Grid e media query para celular
- O formulário é **demonstrativo**: não envia dados nem armazena nada.

## 5. Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/ecomoda-instituto.git
   ```
2. Entre na pasta:
   ```bash
   cd ecomoda-instituto
   ```
3. Abra o arquivo `index.html` no navegador (duplo clique), ou use a extensão *Live Server* do VS Code.

## 6. Segurança

Nenhuma credencial, senha, token ou chave de API é usada ou versionada neste projeto. O `.gitignore` bloqueia arquivos `.env` e chaves por precaução.

## 7. Próximos passos

- Integrar cálculo de frete por CEP e pagamento PIX automático
- Painel de estoque para peças únicas
- Página individual de cada peça com QR code de rastreabilidade

## 8. Licença

Distribuído sob a licença [MIT](LICENSE).

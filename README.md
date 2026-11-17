# iT2x — Site institucional

Site institucional em React e Vite, com conteúdo e identidade visual baseados no PowerPoint da iT2x. Logo, selos, ilustrações, fotos da equipe e marcas parceiras foram extraídos do arquivo original, sem recriar os logotipos.

## Executar

Requer Node.js 22.12+ ou 24 LTS e npm.

```bash
npm install
npm run dev
```

## Produção

```bash
npm run build
npm run preview
```

Publique a pasta `dist` em uma hospedagem estática. Não há banco de dados, coleta de leads ou backend. Os contatos abrem e-mail, telefone ou WhatsApp.

## Conteúdo

- Empresa, indicadores e especializações TOTVS/Microsoft.
- ERP, Cloud Solutions, Process Solutions, Financial Connectivity e Process BPO.
- Áreas de atuação: Protheus, infraestrutura, Service Desk, segurança, BI, apps, projetos e outsourcing.
- Serviços especializados ERP, AMS, sustentação e suporte ao roadmap.
- Apoio fiscal, tributos e obrigações acessórias.
- Microsoft, Azure, Active Directory, identidades e governança.
- Cybersegurança 360°, continuidade e recuperação de desastres.
- Benefícios da terceirização, 15 marcas parceiras e os três especialistas do portfólio.
- Canais de contato, endereço e área do cliente.

## Arquivos

- `src/main.jsx`: componentes e seções da página.
- `src/content.js`: listas de serviços, parceiros e equipe.
- `src/styles.css`: cores do portfólio, layout responsivo e animações.
- `public/brand/`: imagens originais extraídas da apresentação.
- `index.html`: metadados e favicon usando o logo institucional.

Paleta do PowerPoint: `#072449`, `#012849`, `#1C73A9`, `#5DE1E6`, `#B2C5D6`. Tipografia: Roboto e League Spartan, carregadas por Google Fonts, com fallback local. A apresentação original permanece local e é ignorada pelo Git.

A abertura usa a ilustração institucional em uma composição com perspectiva CSS e resposta ao ponteiro. Há controle para pausar as animações e respeito à preferência de movimento reduzido do sistema. Serviços adicionais são apresentados em painéis expansíveis nativos, acessíveis por teclado.

Dados comerciais e contatos seguem a apresentação fornecida. O link de privacidade aponta para o site institucional atual. Não foram adicionados analytics ou cookies de rastreamento.

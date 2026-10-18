<img src="./.github/screenshots/header.png#gh-light-mode-only" width="100%" alt="Header light mode"/>
<img src="./.github/screenshots/header-dark.png#gh-dark-mode-only" width="100%" alt="Header dark mode"/>

___

# Chatwoot

The modern customer support platform, an open-source alternative to Intercom, Zendesk, Salesforce Service Cloud etc.

<p>
  <img src="https://img.shields.io/circleci/build/github/chatwoot/chatwoot" alt="CircleCI Badge">
    <a href="https://hub.docker.com/r/chatwoot/chatwoot/"><img src="https://img.shields.io/docker/pulls/chatwoot/chatwoot" alt="Docker Pull Badge"></a>
  <a href="https://hub.docker.com/r/chatwoot/chatwoot/"><img src="https://img.shields.io/docker/cloud/build/chatwoot/chatwoot" alt="Docker Build Badge"></a>
  <img src="https://img.shields.io/github/commit-activity/m/chatwoot/chatwoot" alt="Commits-per-month">
  <a title="Crowdin" target="_self" href="https://chatwoot.crowdin.com/chatwoot"><img src="https://badges.crowdin.net/e/37ced7eba411064bd792feb3b7a28b16/localized.svg"></a>
  <a href="https://discord.gg/cJXdrwS"><img src="https://img.shields.io/discord/647412545203994635" alt="Discord"></a>
  <a href="https://status.chatwoot.com"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fchatwoot%2Fstatus%2Fmaster%2Fapi%2Fchatwoot%2Fuptime.json" alt="uptime"></a>
  <a href="https://status.chatwoot.com"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fchatwoot%2Fstatus%2Fmaster%2Fapi%2Fchatwoot%2Fresponse-time.json" alt="response time"></a>
  <a href="https://artifacthub.io/packages/helm/chatwoot/chatwoot"><img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/artifact-hub" alt="Artifact HUB"></a>
</p>


<p>
  <a href="https://heroku.com/deploy?template=https://github.com/chatwoot/chatwoot/tree/master" alt="Deploy to Heroku">
     <img width="150" alt="Deploy" src="https://www.herokucdn.com/deploy/button.svg"/>
  </a>
  <a href="https://marketplace.digitalocean.com/apps/chatwoot?refcode=f2238426a2a8" alt="Deploy to DigitalOcean">
     <img width="200" alt="Deploy to DO" src="https://www.deploytodo.com/do-btn-blue.svg"/>
  </a>
</p>

<img src="./.github/screenshots/dashboard.png#gh-light-mode-only" width="100%" alt="Chat dashboard dark mode"/>
<img src="./.github/screenshots/dashboard-dark.png#gh-dark-mode-only" width="100%" alt="Chat dashboard"/>

---

Chatwoot is the modern, open-source, and self-hosted customer support platform designed to help businesses deliver exceptional customer support experience. Built for scale and flexibility, Chatwoot gives you full control over your customer data while providing powerful tools to manage conversations across channels.

### ✨ Captain – AI Agent for Support

Supercharge your support with Captain, Chatwoot’s AI agent. Captain helps automate responses, handle common queries, and reduce agent workload—ensuring customers get instant, accurate answers. With Captain, your team can focus on complex conversations while routine questions are resolved automatically. Read more about Captain [here](https://chwt.app/captain-docs).

### 💬 Omnichannel Support Desk

Chatwoot centralizes all customer conversations into one powerful inbox, no matter where your customers reach out from. It supports live chat on your website, email, Facebook, Instagram, Twitter, WhatsApp, Telegram, Line, SMS etc.

### 📚 Help center portal

Publish help articles, FAQs, and guides through the built-in Help Center Portal. Enable customers to find answers on their own, reduce repetitive queries, and keep your support team focused on more complex issues.

### 🗂️ Other features

#### Collaboration & Productivity

- Private Notes and @mentions for internal team discussions.
- Labels to organize and categorize conversations.
- Keyboard Shortcuts and a Command Bar for quick navigation.
- Canned Responses to reply faster to frequently asked questions.
- Auto-Assignment to route conversations based on agent availability.
- Multi-lingual Support to serve customers in multiple languages.
- Custom Views and Filters for better inbox organization.
- Business Hours and Auto-Responders to manage response expectations.
- Teams and Automation tools for scaling support workflows.
- Agent Capacity Management to balance workload across the team.

#### Customer Data & Segmentation
- Contact Management with profiles and interaction history.
- Contact Segments and Notes for targeted communication.
- Campaigns to proactively engage customers.
- Custom Attributes for storing additional customer data.
- Pre-Chat Forms to collect user information before starting conversations.

#### Integrations
- Slack Integration to manage conversations directly from Slack.
- Dialogflow Integration for chatbot automation.
- Dashboard Apps to embed internal tools within Chatwoot.
- Shopify Integration to view and manage customer orders right within Chatwoot.
- Use Google Translate to translate messages from your customers in realtime.
- Create and manage Linear tickets within Chatwoot.

#### Reports & Insights
- Live View of ongoing conversations for real-time monitoring.
- Conversation, Agent, Inbox, Label, and Team Reports for operational visibility.
- CSAT Reports to measure customer satisfaction.
- Downloadable Reports for offline analysis and reporting.


## Documentation

Detailed documentation is available at [chatwoot.com/help-center](https://www.chatwoot.com/help-center).

## Translation process

The translation process for Chatwoot web and mobile app is managed at [https://translate.chatwoot.com](https://translate.chatwoot.com) using Crowdin. Please read the [translation guide](https://www.chatwoot.com/docs/contributing/translating-chatwoot-to-your-language) for contributing to Chatwoot.

## Branching model

We use the [git-flow](https://nvie.com/posts/a-successful-git-branching-model/) branching model. The base branch is `develop`.
If you are looking for a stable version, please use the `master` or tags labelled as `v1.x.x`.

## Deployment

### Heroku one-click deploy

Deploying Chatwoot to Heroku is a breeze. It's as simple as clicking this button:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/chatwoot/chatwoot/tree/master)

Follow this [link](https://www.chatwoot.com/docs/environment-variables) to understand setting the correct environment variables for the app to work with all the features. There might be breakages if you do not set the relevant environment variables.


### DigitalOcean 1-Click Kubernetes deployment

Chatwoot now supports 1-Click deployment to DigitalOcean as a kubernetes app.

<a href="https://marketplace.digitalocean.com/apps/chatwoot?refcode=f2238426a2a8" alt="Deploy to DigitalOcean">
  <img width="200" alt="Deploy to DO" src="https://www.deploytodo.com/do-btn-blue.svg"/>
</a>

### Other deployment options

For other supported options, checkout our [deployment page](https://chatwoot.com/deploy).

## Security

Looking to report a vulnerability? Please refer our [SECURITY.md](./SECURITY.md) file.

## Community

If you need help or just want to hang out, come, say hi on our [Discord](https://discord.gg/cJXdrwS) server.

## Como rodar localmente

Stack de Community Edition. A imagem sai do `docker/Dockerfile` deste repositório. Precisa do [Docker Desktop](https://www.docker.com/products/docker-desktop/) no Windows, macOS ou Linux. No Linux também serve o Docker Engine com o plugin Compose.

Na raiz do repositório:

```bash
cp docker/env.example .env
docker compose -f docker-compose.local.yml build
docker compose -f docker-compose.local.yml run --rm rails bundle exec rails db:chatwoot_prepare
docker compose -f docker-compose.local.yml up -d
```

Abra http://localhost:3000. Na primeira subida o app mostra o formulário de instalação (nome, empresa, e-mail, senha). Esse formulário cria o super admin e a primeira conta. Deixe desmarcada a opção de receber novidades: ela registra a instância no hub do upstream. O título e o logo são o placeholder **Inbox**.

`ENABLE_ACCOUNT_SIGNUP` no `.env` não liga o cadastro público depois do `db:chatwoot_prepare`. O valor que vale é o de `installation_configs`, semeado como `false` em `config/installation_config.yml`. **false é o padrão de produção**: conta nova nasce pela API da agenda, não pelo formulário público. Se o formulário de instalação já foi concluído, crie outro admin com:

```bash
docker compose -f docker-compose.local.yml exec rails bundle exec rails runner "admin = SuperAdmin.new(name: 'Admin', email: 'admin@example.com', password: 'Password1!'); admin.skip_confirmation!; admin.save!; account = Account.create!(name: 'Local', locale: 'pt_BR'); AccountUser.create!(account: account, user: admin, role: :administrator)"
```

Entre em http://localhost:3000 com `admin@example.com` / `Password1!`. O Super Admin fica em http://localhost:3000/super_admin/sign_in. Troque a senha e o `SECRET_KEY_BASE` do `.env` antes de qualquer uso que não seja a sua máquina. Para ligar o cadastro público só neste ambiente, no Super Admin abra Installation Configs e mude `ENABLE_ACCOUNT_SIGNUP` para `true`.

Para parar: `docker compose -f docker-compose.local.yml down`. Os dados ficam nos volumes. `docker compose -f docker-compose.local.yml down -v` apaga o banco.

`docker-compose.yaml` na raiz é o stack de desenvolvimento do upstream (Rails em modo development, Vite, Mailhog). O fluxo desta seção é o arquivo `docker-compose.local.yml`.

### Marca (placeholder)

O nome e o logo ainda não foram escolhidos. O placeholder é **Inbox**, para a palavra e o desenho do Chatwoot não aparecerem para quem usa o produto. Identificadores de código, módulos Ruby e o nome do repositório continuam iguais. A licença MIT e o copyright do upstream ficam intactos.

Onde trocar quando a marca existir:

| O quê | Onde |
|---|---|
| Nome da instalação, nome da marca, URLs de termos, privacidade e "powered by", caminhos dos logos | `config/installation_config.yml` (`INSTALLATION_NAME`, `BRAND_NAME`, `BRAND_URL`, `WIDGET_BRAND_URL`, `LOGO`, `LOGO_THUMBNAIL`, `LOGO_DARK`, `TERMS_URL`, `PRIVACY_URL`). `locked: false`, então o Super Admin também edita em Installation Configs. Num banco que já subiu, editar o YAML não sobrescreve o valor antigo: mude na tela ou rode o ConfigLoader com `reconcile_only_new: false`. |
| Logo da tela de login (claro e escuro) e favicon | `public/brand-assets/logo.svg`, `logo_dark.svg`, `logo_thumbnail.svg`. O favicon da página é `LOGO_THUMBNAIL`. |
| Avatar padrão do bot no widget | `public/assets/images/chatwoot_bot.png` (o nome do arquivo é interno; troque só o desenho). |
| Fallback do ícone quando `LOGO_THUMBNAIL` está vazio | `app/javascript/dashboard/components-next/icon/Logo.vue` |
| Remetente dos e-mails | `MAILER_SENDER_EMAIL` no `.env` |
| Manifesto (nome "Inbox") | `public/manifest.json`. Ele não é publicado enquanto `DISPLAY_MANIFEST` for `false`. |

`DISPLAY_MANIFEST` fica `false` de propósito. Com `true`, o HTML também aponta para os PNG em `public/favicon-*.png`, `public/apple-icon*.png`, `public/android-icon-*.png` e `public/ms-icon-*.png`, que ainda são as marcas do upstream. Troque esses arquivos antes de ligar a flag.

Textos de interface continuam com a palavra "Chatwoot" nos arquivos de idioma. `replaceInstallationName` (`app/javascript/shared/composables/useBranding.js`) troca essa palavra pelo `INSTALLATION_NAME` na hora de renderizar (login, "powered by" do widget, etc.). Não renomeie as chaves de i18n. A troca só pega a palavra em alfabeto latino; um locale que transliterou o nome não é substituído. Em pt-BR a palavra está intacta, então a troca funciona.

Se `BRAND_NAME` ficar vazio, o layout de e-mail (`app/views/layouts/mailer/base.liquid`) e `app/views/devise/mailer/confirmation_instructions.html.erb` ainda caem na palavra Chatwoot. Mantenha `BRAND_NAME` preenchido.

### Sincronizar com o upstream

```bash
git remote add upstream https://github.com/chatwoot/chatwoot.git   # só na primeira vez
git fetch upstream
git checkout develop
git merge upstream/develop
```

O merge traz de volta `enterprise/` e `spec/enterprise/`. Este fork não publica esse código. Apague as duas árvores, no mesmo passo do workflow `publish_foss_docker.yml`, e commite:

```bash
rm -rf enterprise spec/enterprise
git add -A enterprise spec/enterprise
git commit -m "chore: drop enterprise trees after upstream merge"
```

O workflow `.github/workflows/ce_only_guard.yml` falha se qualquer uma das pastas voltar a existir.

## Contributors

Thanks goes to all these [wonderful people](https://www.chatwoot.com/docs/contributors):

<a href="https://github.com/chatwoot/chatwoot/graphs/contributors"><img src="https://opencollective.com/chatwoot/contributors.svg?width=890&button=false" /></a>


*Chatwoot* &copy; 2017-2026, Chatwoot Inc - Released under the MIT License.

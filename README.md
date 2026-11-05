# Barbearia Jocitan Rezende

Landing page da **Barbearia Jocitan Rezende**, em Nova Friburgo – RJ. Apresenta a barbearia, os serviços e a localização, e leva o cliente direto para o agendamento online ou para o WhatsApp.

> Barba • Cabelo • Bigode — *Comprometimento e qualidade é a nossa marca.*

## Funcionalidades

- **Agendamento rápido:** botão flutuante "Agendar horário" sempre visível, ligado ao [Agendei Fácil](https://agendeifacil.com/booking/7642).
- **WhatsApp:** botão flutuante e seção de contato com mensagem já preenchida, para quem quer um trabalho mais detalhado.
- **Serviços organizados** em quatro grupos (Cortes, Barba e combos, Coloração e tratamentos, Estética e cuidados), com o tempo de atendimento. Os valores ficam no agendamento online.
- **Localização:** mapa embutido e endereço clicável que abre a ficha da barbearia no Google Maps, além do botão "Como chegar".
- **Identidade visual:** logo, fachada da barbearia e ícone na aba do navegador.
- **Responsivo:** feito para celular, tablet e computador.

## Tecnologias

| Para quê | O que foi usado |
|---|---|
| Estrutura | HTML5 |
| Estilo e layout responsivo | CSS3 (Grid, Flexbox, variáveis CSS) |
| Interações | JavaScript puro (sem frameworks) |
| Fontes | Google Fonts (Cinzel e Inter) |
| Mapa | Google Maps (incorporado e links) |
| Agendamento | Agendei Fácil |
| Contato | WhatsApp (`wa.me`) |

Não há etapa de build nem dependências para instalar: é um site estático.

## Estrutura do projeto

```
├── index.html            # página completa (HTML + CSS + JS)
├── logo.png              # logo da barbearia
├── fachada.jpg           # foto da fachada
├── favicon.ico           # ícone da aba
├── favicon-32.png
├── favicon-48.png
├── apple-touch-icon.png  # ícone ao salvar na tela inicial do iPhone
├── icon-192.png
└── icon-512.png
```

## Como rodar localmente

Basta abrir o `index.html` no navegador. Se preferir um servidor local:

```bash
npx serve .
```

## Como publicar

**Pelo GitHub (publicação automática a cada commit)**

1. Na [Vercel](https://vercel.com), escolha **Add New → Project** e importe este repositório.
2. Em **Framework Preset**, deixe **Other**. Não é preciso Build Command nem Output Directory.
3. Clique em **Deploy**.

Netlify e Cloudflare Pages funcionam do mesmo jeito.

**Arrastando os arquivos:** acesse [vercel.com/drop](https://vercel.com/drop) e arraste a pasta do projeto.

## Como personalizar

Procure estes trechos no `index.html`:

| O que mudar | Onde |
|---|---|
| Link de agendamento | `https://agendeifacil.com/booking/7642` |
| Número do WhatsApp | `5522992347423` |
| Endereço e mapa | seção `#local` |
| Serviços | seção `#servicos` |
| Instagram | `instagram.com/jocitan_rezendebarbearia` |

## Contato da barbearia

- **Endereço:** Rua Joaquim da Rosa Pinheiro, 620 – Jardim California, Nova Friburgo – RJ, CEP 28633-790
- **WhatsApp:** (22) 99234-7423
- **Instagram:** [@jocitan_rezendebarbearia](https://www.instagram.com/jocitan_rezendebarbearia)
- **Agendamento:** [agendeifacil.com/booking/7642](https://agendeifacil.com/booking/7642)

## Créditos

Site desenvolvido por [VCRK Digital](https://www.instagram.com/vcrk.digital).

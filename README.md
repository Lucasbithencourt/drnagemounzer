# Landing Page — Dr. Nage Mounzer | Dermatologia

> ⚠️ **Protótipo de prospecção comercial — não é o site oficial do profissional.**
> Página desenvolvida como demonstração/proposta. Textos, imagens e informações
> ainda dependem de validação e autorização do titular.

Landing page de conversão para o Dr. Nage Mounzer, dermatologista clínico e cirúrgico
em Criciúma-SC. Objetivo: gerar agendamento de consulta via WhatsApp.

## Stack

- HTML5 semântico
- CSS puro (sem framework), com variáveis de tema em `:root`
- Google Fonts: **Fraunces** (títulos) + **Inter** (corpo)

## Estrutura de arquivos

```
.
├── index.html      # Marcação da página (10 seções)
├── style.css       # Estilos, paleta e responsividade
└── README.md
```

## Como rodar localmente

Por usar caminhos relativos e fontes externas, o ideal é servir por um servidor local
(em vez de abrir o arquivo direto pelo `file://`).

**Com Python 3:**

```bash
python3 -m http.server 8000
```

**Com Node (npx):**

```bash
npx serve
```

Depois abra no navegador: `http://localhost:8000`

## Notas de conteúdo

- Sem preços, promoções ou notas de avaliação inventadas.
- Procedimentos cirúrgicos (câncer de pele, remoção de lesões) tratados apenas em
  texto/credencial, sem imagens gráficas.
- Pontos marcados por comentário no HTML onde entram os materiais reais:
  foto autorizada do profissional, imagens de resultado (com consentimento) e o mapa.

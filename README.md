
<div align="center">

# 🌊 Quiz Nadador-Salvador

**Plataforma de estudo interativa para o Curso de Nadador-Salvador (EEAT)**

[![Live Demo](https://img.shields.io/badge/▶%20Demo%20ao%20Vivo-0284c7?style=for-the-badge&logoColor=white)](https://anacleto-pt.github.io/EEAT_NS/)
[![HTML](https://img.shields.io/badge/HTML-Single%20File-e34f26?style=for-the-badge&logo=html5&logoColor=white)](index.html)
[![License](https://img.shields.io/badge/Licença-MIT-22c55e?style=for-the-badge)](LICENSE)

<br>

> *257 perguntas · 9 capítulos · 10 cenários práticos · Zero instalação*

</div>

---

## Sobre o projeto

Este quiz foi desenvolvido como ferramenta de preparação para o exame do Curso de **Nadador-Salvador (NS)** da EEAT. Corre inteiramente no browser — sem servidor, sem base de dados, sem conta — e pode ser instalado como app no telemóvel via PWA.

O conteúdo cobre desde a história e legislação do salvamento aquático até aos protocolos clínicos de SBV, OVA, oxigenoterapia e imobilização de vítimas com trauma.

---

## Modos de estudo

### 🎲 Aleatório Total
Todas as 257 perguntas em ordem aleatória. Para quem quer uma sessão longa de revisão sem filtros.

### 📚 Por Capítulo
Estuda um capítulo de cada vez. Útil para focar nas áreas com mais dificuldade.

| Capítulo | Tema | Perguntas |
|:---:|---|:---:|
| 1 | História e Enquadramento do Salvamento Aquático | 28 |
| 2 | Conduta e Perfil do Nadador-Salvador | 33 |
| 3 | Legislação e Regulamentação | 19 |
| 4 | Prevenção e Vigilância | 31 |
| 5 | Técnicas de Salvamento Aquático | 24 |
| 6 | Suporte Básico de Vida (SBV) | 29 |
| 7 | Obstrução da Via Aérea e Oxigenoterapia | 50 |
| 8 | Trauma e Imobilização | 40 |
| 9 | Situações Especiais | 3 |

### ⏱ Teste Cronometrado
Simulação real do exame: **20 perguntas · 2 por capítulo · 20 minutos**. As perguntas são selecionadas aleatoriamente de cada capítulo e apresentadas em ordem mista — exatamente como no exame real.

### 📋 Ordenação de Procedimentos
O modo mais exigente. Apresenta o **enquadramento clínico completo** de cada um dos 10 cenários teórico-práticos e pede para ordenar os passos de intervenção na sequência correta, por drag-and-drop.

| Cenário | Situação |
|:---:|---|
| 01 | Afogamento adulto · SBV Afogamento · O₂ inalação |
| 02 | Vítima inanimada adulto · SBV · O₂ inalação |
| 03 | Afogamento pediátrico · SBV Afogamento · O₂ inalação |
| 04 | Vítima inanimada criança · SBV Pediátrico · O₂ inalação |
| 05 | Obstrução via aérea grávida · OVA · O₂ insuflação |
| 06 | Obstrução via aérea lactente · OVA · O₂ insuflação |
| 07 | Dificuldade respiratória consciente → paragem · ABCDE · O₂ |
| 08 | Afogamento + trauma cervical · SBV · Imobilização · O₂ |
| 09 | Trauma em piscina · ABCDE · Imobilização · O₂ |
| 10 | Trauma em piscina + insuflação → imobilização · O₂ |

---

## Funcionalidades

- **Feedback imediato** — resposta certa/errada com destaque visual após cada pergunta
- **Revisão completa** — no fim de qualquer teste, revê todas as perguntas com as respostas dadas, corretas e erradas assinaladas
- **Persistência de sessão** — o progresso é guardado automaticamente; se fechar o browser a meio, retoma exatamente onde parou
- **Drag-and-drop fluido** — nos cenários de ordenação, os itens seguem o cursor/dedo em tempo real com reordenação dinâmica dos restantes
- **Dark / Light mode** — toggle com preferência guardada; respeita o tema do sistema por omissão
- **Estatísticas globais** — histórico de sessões, taxa de acerto por capítulo e progresso acumulado
- **Navegação direta** — vai para qualquer pergunta pelo número sem percorrer todo o quiz
- **PWA instalável** — funciona offline e pode ser adicionado ao ecrã inicial como app nativa

---

## Instalação como app (PWA)

Não requer instalação de loja. No telemóvel Android:

1. Abre o [link da demo](https://anacleto-pt.github.io/EEAT_NS/) no **Chrome**
2. Toca nos três pontos `⋮` no canto superior direito
3. Seleciona **"Adicionar ao ecrã inicial"**
4. Confirma — aparece um ícone como qualquer outra app

---

## Uso local

Não precisa de servidor. Faz download do ficheiro e abre diretamente no browser:

```bash
git clone https://github.com/anacleto-pt/EEAT_NS.git
open EEAT_NS/index.html
```

Ou simplesmente faz download do `index.html` e abre com duplo clique.

---

## Estrutura do projeto
```
EEAT_NS/
└── index.html          # Aplicação completa — HTML + CSS + JS num único ficheiro
```

Toda a lógica, estilos e dados vivem num único ficheiro autocontido. Sem dependências externas além das fontes Google Fonts (carregadas via CDN).

---

## Tecnologias

- **HTML5 / CSS3 / JavaScript** — sem frameworks, sem build tools
- **CSS Custom Properties** — sistema de tokens para light/dark mode
- **Touch & Mouse Events** — drag-and-drop nativo sem bibliotecas
- **localStorage** — persistência de progresso e preferências
- **Google Fonts** — Barlow Condensed + Inter

---

## Contribuir

Se encontrares uma pergunta incorreta, um cenário desatualizado ou quiseres adicionar conteúdo:

1. Faz fork do repositório
2. Edita o array `QUESTIONS` ou os cenários de ordenação em `index.html`
3. Abre um Pull Request com a descrição da alteração

---

<div align="center">

Desenvolvido para uso pessoal durante a preparação para o exame EEAT de Nadador-Salvador.

**Boa sorte no exame. 🏖️**

</div>

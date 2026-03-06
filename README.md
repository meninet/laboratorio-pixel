# 🔬 Laboratório Pixel: A Missão das Fases

## Ficha Técnica

**Nome:** Laboratório Pixel: A Missão das Fases
**Componente curricular:** Ciências — 6º ano do Ensino Fundamental (Anos Finais)
**Habilidade BNCC:** EF06CI01 — Classificar como homogênea ou heterogênea a mistura de dois ou mais materiais (água e sal, água e óleo, água e areia etc.)
**Descritor SAEB:** E1B1 — Classificar a mistura de dois ou mais materiais como homogênea ou heterogênea e o respectivo método de separação
**Unidade temática:** Matéria e Energia — Misturas homogêneas e heterogêneas
**Duração estimada:** 20–30 minutos
**Formato:** HTML autocontido (arquivo único, sem dependências externas)

---

## Sinopse

O robô Pixel é o assistente de um grande laboratório escolar de Ciências. Um carregamento de amostras misteriosas chegou e o laboratório está uma bagunça! Pixel precisa da ajuda de um jovem cientista (o estudante) para analisar, classificar e separar todas as misturas antes que o laboratório fique em caos total.

Ao longo de 4 fases progressivas, o estudante aprende a observar fases, classificar misturas, usar o microscópio para desmascarar coloides e escolher métodos de separação — culminando num desafio final sobre o tratamento de água.

---

## Estrutura do Jogo

### Telas Iniciais

- **Tela de Abertura** — Nome do jogo, sinopse, códigos curriculares (BNCC/SAEB) e botão "Iniciar Missão"
- **Tela de Nome + Aprendizagens** — Diálogo do Pixel, lista "Você vai aprender" com 6 objetivos, campo de nome do aluno e rodapé informativo

### Fase 1 — O Treinamento (6 questões)

**Objetivo:** Observar e identificar quantas fases existem em uma mistura.
**Mecânica:** Escolha binária — "1 FASE (Uniforme)" ou "2+ FASES (Diferente)"
**Cards de aula:** 4 (Antes e Depois, O que é uma Mistura, O que é uma Fase, Como Observar)
**Amostras:** Água Pura, Água + Areia, Água + Óleo, Suco de Limão Coado, Salada de Frutas, Café com Leite

### Fase 2 — O Classificador (12 questões)

**Objetivo:** Classificar misturas como homogêneas ou heterogêneas.
**Mecânica:** Escolha binária — "HOMOGÊNEA" ou "HETEROGÊNEA"
**Cards de aula:** 4 (Homogênea, Heterogênea, Atenção aos Detalhes, Dica do Pixel)
**Amostras:** Água + Sal, Água + Óleo, Ar Atmosférico, Granito, Água com Gás, Ouro 18K, Água + Areia + Serragem, Vinagre, Água + Farinha, Bronze, Água + Gelo, Sopa de Legumes

### Fase 3 — O Microscópio (6 questões)

**Objetivo:** Identificar coloides (misturas que parecem homogêneas a olho nu, mas são heterogêneas no microscópio) e diferenciá-los de soluções verdadeiras.
**Mecânica:** Microscópio interativo + classificação — "HOMOGÊNEA" ou "HETEROGÊNEA (Coloide)"
**Cards de aula:** 4 (Nem tudo que parece é!, Coloides, Soluções Verdadeiras, Sua Missão)
**Amostras:** Leite, Sangue, Soro Fisiológico, Maionese, Gelatina, Tinta Nanquim

### Fase 4 — O Separador (12 questões)

**Objetivo:** Escolher o método de separação adequado para cada mistura.
**Mecânica:** Múltipla escolha (4 opções por questão) + ordenação no desafio final
**Cards de aula:** 8 (Separar Misturas, Catação/Peneiração, Filtração, Decantação/Centrifugação, Sep. Magnética, Ventilação/Flotação/Levigação, Evaporação/Destilação, Sua Missão)
**Métodos cobertos:** Catação, Peneiração, Filtração, Decantação, Separação Magnética, Ventilação, Levigação, Centrifugação, Evaporação, Destilação
**Q1–Q11:** Questões de múltipla escolha com feedback específico por alternativa errada
**Q12 — Desafio Final:** Card explicativo sobre o Tratamento de Água em uma ETA + ordenação das 8 etapas (Captação → Gradeamento → Coagulação/Floculação → Decantação → Filtração → Desinfecção → Correção pH/Fluoretação → Reservatório/Distribuição)

### Tela Final — Certificado

Exibe nome do aluno, título por faixa de desempenho, estrelas, acertos, mensagem narrativa do Pixel, lista "O que você aprendeu" e dados curriculares.

---

## Sistema de Pontuação

- **Métrica principal:** Percentual de acertos de primeira tentativa (sem erro prévio)
- **Estrelas:** ⭐⭐⭐ = 90–100% | ⭐⭐ = 70–89% | ⭐ = 50–69% | Sem estrela = abaixo de 50%
- **Dicas:** Gratuitas — usar dica não desconta pontos
- **Erros:** Acertar após errar = 0 pontos na questão (apenas feedback formativo). A alternativa errada fica desabilitada
- **Total de questões:** 36 (6 + 12 + 6 + 12)

### Faixas de Desempenho no Certificado

| Faixa | Título | Emoji |
|-------|--------|-------|
| 90–100% | Mestre das Misturas | 🏆 |
| 70–89% | Cientista Pleno | 🥈 |
| 50–69% | Cientista Júnior | 🥉 |
| < 50% | Aprendiz de Laboratório | 🔬 |

---

## Sistema de Feedback

### Fases 1 a 3 (escolha binária)

Cada questão possui 3 níveis de feedback:
- **Acerto:** Feedback positivo com explicação científica
- **Erro (com nova tentativa):** Feedback orientador que guia o raciocínio sem dar a resposta
- **Erro (sem nova tentativa):** Feedback final com a explicação completa

### Fase 4 (múltipla escolha)

Cada alternativa errada possui um feedback específico que explica por que aquele método não é o adequado e direciona o raciocínio para o método correto.

### Q12 (ordenação)

- Ordem correta: Feedback de acerto completo
- Parcialmente errada: Feedback orientador com lógica do caminho da água
- Muito errada: Feedback com sequência lógica detalhada

---

## Aspectos Técnicos

- **Formato:** HTML autocontido — arquivo único sem dependências de servidor
- **Estilo visual:** Pixel Art / Retrô com paleta Pico-8 (16 cores neon sobre fundo escuro)
- **Personagem guia:** Pixel — robô assistente com expressões faciais (feliz/triste/neutro)
- **Sons:** Sintetizados em tempo real (Web Audio API) — 8-bit: acerto, erro, estrela, clique, digitação
- **Responsivo:** Adaptado para desktop, tablet e celular (breakpoints: 768px e 480px)
- **Acessibilidade:** Fontes pixel art legíveis, alto contraste, botões com áreas de clique amplas

---

## Como Usar

1. Abra o arquivo `Laboratorio-Pixel-FINAL.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari)
2. Não é necessário conexão com internet após o carregamento inicial da fonte (Google Fonts)
3. O jogo funciona 100% offline após o primeiro carregamento
4. Pode ser distribuído por pen drive, Google Drive, plataformas LMS ou hospedado em qualquer servidor web estático

---

## Pré-requisitos do Estudante

- Conceitos básicos de estados físicos da matéria (sólido, líquido, gasoso)
- Noção de que matéria é feita de materiais diferentes

---

## Créditos

**Desenvolvimento:** Ciência Plural — TRIade Plural
**Site:** cienciaplural.com.br
**Versão:** Regular (sem adaptações AEE)

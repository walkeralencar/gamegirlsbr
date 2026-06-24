# Prompt Template: Sci-Fi UAI

## Uso

Use este template para gerar o prompt final de geração de imagem após completar a análise e estrutura visual.

---

## Template Base

```
Transforme o conteúdo fornecido em um infográfico vertical no estilo Sci-Fi UAI.

Objetivos:
- Máxima autoridade visual
- Alta densidade de informação (80%)
- Aparência de sistema operacional futurista
- Estética premium
- Pronto para LinkedIn e Instagram

Características visuais:
- HUD futurista com painéis e bordas #223D75
- KPI Cards com números em destaque
- Rankings horizontais com barras futuristas
- Gráficos: [SELECIONAR TIPO]
- Conexões visuais entre blocos de dados
- Microdetalhes: SYS-01, LIVE DATA, SYNC 98%, UPLINK ACTIVE
- Paleta: Background #050816, Cyan #00E5FF, Purple #7C4DFF
- Tipografia pesada (900 weight) para valores principais

Formato: 1080x1920

Estrutura:
1. Header — [TÍTULO] + [SUBTÍTULO] + ID sistêmico
2. BLOCK-01 — [TIPO]: [DADOS]
3. BLOCK-02 — [TIPO]: [DADOS]
4. BLOCK-03 — [TIPO]: [DADOS]
5. BLOCK-04 — [TIPO]: [DADOS] (opcional)
6. Footer — Conclusão + metadados sistêmicos

Modo: [Executive | Command Center | Impact | Gamer]

Densidade: 80%

Estética:
Sci-Fi UAI / Cyberpunk Elegante / Data Intelligence / Enterprise Dashboard / AI Operating System
```

---

## Variações por Modo

### Executive
> Paleta mais sóbria. KPIs em destaque máximo. Menos microdetalhes lúdicos. Ideal para relatórios corporativos.

### Command Center
> Máxima densidade. Múltiplos painéis simultâneos. Data Grids e Network Graphs. Sensação de monitoramento em tempo real.

### Impact
> Dados com maior apelo emocional no topo. Storytelling visual. Rankings de impacto. Social-first.

### Gamer
> XP bars, progressão, rankings de jogadores. Elementos lúdicos dentro do Sci-Fi UAI. Pink `#FF4FCB` como acento.

---

## Instruções para Claude

Ao usar este template:

1. **Preencher todos os placeholders** `[...]` com dados reais extraídos do conteúdo.
2. **Não enviar o template em branco** — Claude deve completar antes de entregar.
3. **Especificar o tipo de gráfico exato** por bloco (não usar "algum gráfico").
4. **Incluir os valores numéricos reais** nos labels dos componentes.
5. Após gerar o prompt, executar validação contra `qa-checklist.md`.

# Sci-Fi UAI Design System

## Paleta

### Base

| Token | Hex | Uso |
|---|---|---|
| Background | `#050816` | Fundo principal |
| Surface | `#0A1022` | Painéis internos |
| Panel | `#101A35` | Cards e seções |
| Borders | `#223D75` | Divisores e bordas |

### Destaques

| Token | Hex | Uso |
|---|---|---|
| Cyan | `#00E5FF` | Primário / CTA visual |
| Blue | `#4FC3F7` | Dados secundários |
| Purple | `#7C4DFF` | Acento / destaque |
| Pink | `#FF4FCB` | Alerta positivo / gaming |

### Alertas

| Token | Hex | Uso |
|---|---|---|
| Success | `#00E676` | Métricas positivas |
| Warning | `#FFD600` | Alertas e avisos |
| Danger | `#FF5252` | Erros e críticos |

### Texto

| Token | Hex |
|---|---|
| Primary | `#FFFFFF` |
| Secondary | `#B0BEC5` |
| Muted | `#78909C` |

---

## Layout

Formato: **Vertical**

Dimensões:
- `1080 × 1920` (padrão Instagram/LinkedIn)
- `1350 × 2400` (alta densidade)

Estrutura:
- 1 Header
- 3–5 Blocos Principais
- 1 Footer / Conclusão

Fluxo: Top → Bottom (sem navegação lateral)

---

## Hierarquia Tipográfica

| Nível | Uso | Tamanho | Peso |
|---|---|---|---|
| N1 | Título Principal | 48–72px | 900 |
| N2 | Indicadores / KPIs | 36–48px | 700 |
| N3 | Subtítulos de Bloco | 24–32px | 600 |
| N4 | Descrição / Labels | 16–20px | 400 |

---

## Componentes Obrigatórios

Todo layout deve possuir pelo menos:

- ✓ Painéis HUD com bordas `#223D75`
- ✓ KPI Cards com valor em destaque
- ✓ Rankings horizontais
- ✓ Timelines ou fluxos
- ✓ Data Grids / tabelas compactas
- ✓ Progress Indicators (circular ou linear)
- ✓ Linhas de conexão visual entre dados
- ✓ Labels sistêmicos (`SYS-01`, `NODE-08`, `AI CORE`)
- ✓ Coordenadas fictícias de localização ou referência
- ✓ IDs de sistema (`LIVE DATA`, `SYNC 98%`, `UPLINK ACTIVE`)

---

## Tipos de Gráficos (por prioridade)

1. Ranking Horizontal
2. Barras Futuristas
3. Radar / Spider Chart
4. Timeline
5. Heatmap
6. KPI Cards
7. Circular Progress
8. Network Graph
9. Comparação Lado a Lado
10. Fluxo de Impacto

---

## Densidade

| Nível | % |
|---|---|
| Baixa | 20% |
| Média | 50% |
| Alta | 80% |
| **Padrão Sci-Fi UAI** | **70–85%** |

---

## Microdetalhes Técnicos

Adicionar como suporte visual (nunca como elemento principal):

```
SYS-01 / NODE-08 / AI CORE
LIVE DATA / SYNC 98% / UPLINK ACTIVE
DATA STREAM / NEURAL LINK
LAT: -23.5505 LON: -46.6333
T+00:04:32 / FRAME 0847
```

---

## Anti-padrões

- ❌ Fotos genéricas ou stock
- ❌ Emojis
- ❌ Gradientes exagerados
- ❌ Glassmorphism excessivo
- ❌ Excesso de neon sem controle
- ❌ Blocos longos de texto corrido
- ❌ Elementos puramente decorativos
- ❌ Cartoon ou ilustração infantil
- ❌ Ícones aleatórios sem contexto

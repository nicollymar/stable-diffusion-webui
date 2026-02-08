# 5. Elementos de UI

## 5.1 Design System Overview

O Design System do **reticências** é construído com foco em **acessibilidade, clareza e tranquilidade**. Cada componente foi desenvolvido para transmitir segurança e facilitar a navegação, especialmente para usuários em estados de vulnerabilidade emocional.

---

## 5.2 Componentes Principais

### 5.2.1 Botões

#### Botão Primário
**Aparência**:
- Background: Sunset Amber (#F4A261)
- Text: White (#FFFFFF)
- Border: None
- Border Radius: 12px
- Padding: 14px 24px
- Font: Inter Semi Bold 16px
- Min Width: 120px
- Height: 48px

**Estados**:
- **Hover**: Background Sunset Amber + 10% darker, elevação suave (shadow)
- **Active/Pressed**: Background Sunset Amber + 15% darker, sem shadow
- **Focus**: Outline 3px solid Sunset Amber com 30% opacidade, offset 2px
- **Disabled**: Background #DEE2E6, Text #ADB5BD, cursor not-allowed

**Uso**: Ações principais, CTAs importantes, conclusão de fluxos

---

#### Botão Secundário
**Aparência**:
- Background: Transparent
- Text: Sea Deep (#2A4858)
- Border: 2px solid Sea Deep
- Border Radius: 12px
- Padding: 12px 24px
- Font: Inter Semi Bold 16px
- Height: 48px

**Estados**:
- **Hover**: Background Sea Deep 5% opacidade, border mais escuro
- **Active**: Background Sea Deep 10% opacidade
- **Focus**: Outline 3px solid Sea Deep 30% opacidade
- **Disabled**: Border #DEE2E6, Text #ADB5BD

**Uso**: Ações secundárias, cancelamentos, opções alternativas

---

#### Botão Terciário / Ghost
**Aparência**:
- Background: Transparent
- Text: Sunset Amber (#F4A261)
- Border: None
- Padding: 12px 16px
- Font: Inter Medium 16px

**Estados**:
- **Hover**: Background Sunset Amber 8% opacidade
- **Active**: Background Sunset Amber 15% opacidade
- **Focus**: Outline 3px solid Sunset Amber 30% opacidade
- **Disabled**: Text #ADB5BD

**Uso**: Ações terciárias, links de navegação, ações discretas

---

#### Botão Icon
**Aparência**:
- Size: 40x40px
- Background: Transparent
- Border Radius: 10px
- Icon Color: Sea Deep

**Estados**:
- **Hover**: Background #F8F9FA
- **Active**: Background #E9ECEF
- **Focus**: Outline 2px solid Sea Deep
- **Disabled**: Icon Color #CED4DA

**Uso**: Ações rápidas, favoritar, compartilhar, menu

---

#### Floating Action Button (FAB)
**Aparência**:
- Size: 56x56px
- Background: Gradient (Sunset Amber → Sunrise Gold)
- Icon: White, 24px
- Border Radius: 50%
- Shadow: 0 4px 12px rgba(244, 162, 97, 0.4)

**Estados**:
- **Hover**: Elevação aumentada, shadow mais forte
- **Active**: Elevação reduzida
- **Focus**: Outline 3px solid Sunset Amber 50% opacidade

**Uso**: Adicionar nova entrada no diário, iniciar novo exercício

---

### 5.2.2 Cards

#### Card Padrão
**Aparência**:
- Background: White (#FFFFFF)
- Border: 1px solid #E9ECEF
- Border Radius: 16px
- Padding: 24px
- Shadow: 0 2px 8px rgba(42, 72, 88, 0.08)

**Estados**:
- **Hover**: Shadow aumentado para 0 4px 16px
- **Active/Pressed**: Shadow reduzido
- **Focus**: Outline 2px solid Sunset Amber

**Variações**:
1. **Card de Resumo**: Com ícone, título, descrição e CTA
2. **Card de Estatística**: Número grande, label, gráfico pequeno
3. **Card de Exercício**: Imagem de capa, título, duração, botão
4. **Card de Entrada de Diário**: Data, preview do texto, emoções

---

#### Card Interativo (Clickable)
**Aparência**: Igual ao Card Padrão
**Estados**:
- **Hover**: Transform scale(1.02), shadow intensificado, cursor pointer
- **Active**: Transform scale(0.98)
- **Focus**: Outline 2px solid Sunset Amber, sem transform

**Uso**: Cards que levam a outra tela/modal

---

#### Card de Emoção
**Aparência**:
- Size: Variável (min 100x100px)
- Background: Gradiente suave da cor da emoção
- Border Radius: 20px
- Padding: 16px
- Icon/Emoji: 48px centralizado
- Label: Abaixo do ícone, 14px Medium

**Cores por Emoção**:
- Alegria: Gradiente Sunrise Gold
- Calma: Gradiente Sky Calm
- Tristeza: Gradiente Earth Soft
- Ansiedade: Gradiente Sunset Amber (suave)
- Raiva: #E63946 suavizado

**Uso**: Seleção de humor, registro de emoções

---

### 5.2.3 Formulários

#### Input de Texto
**Aparência**:
- Height: 48px
- Background: White
- Border: 1.5px solid #DEE2E6
- Border Radius: 10px
- Padding: 12px 16px
- Font: Inter Regular 16px
- Color: Sea Deep

**Estados**:
- **Focus**: Border 2px solid Sunset Amber, outline none
- **Error**: Border 2px solid #E63946, mensagem de erro abaixo em vermelho
- **Success**: Border 2px solid #52B788, ícone de check verde
- **Disabled**: Background #F8F9FA, Border #E9ECEF, Text #ADB5BD

**Componentes**:
- **Label**: Acima do input, 14px Medium, Text Primary
- **Helper Text**: Abaixo, 13px Regular, Text Secondary
- **Error Message**: Abaixo, 13px Regular, Error color
- **Icon**: Opcional, 20px, à esquerda ou direita

---

#### Textarea
**Aparência**:
- Min Height: 120px
- Resizable: Vertical
- Outras propriedades iguais ao Input de Texto

**Uso**: Diário emocional, reflexões, notas extensas

---

#### Select / Dropdown
**Aparência**:
- Height: 48px
- Ícone dropdown: Chevron down, 20px
- Demais propriedades iguais ao Input

**Dropdown Menu**:
- Background: White
- Border: 1px solid #DEE2E6
- Border Radius: 12px
- Shadow: 0 4px 16px rgba(0,0,0,0.12)
- Max Height: 300px (scroll se necessário)

**Opção**:
- Padding: 12px 16px
- Hover: Background #F8F9FA
- Selected: Background Sunset Amber 10%, Text Sunset Amber

---

#### Checkbox
**Aparência**:
- Size: 20x20px
- Border: 2px solid #ADB5BD
- Border Radius: 4px
- Background: White

**Estados**:
- **Checked**: Background Sunset Amber, ícone check branco
- **Hover**: Border Sea Deep
- **Focus**: Outline 2px solid Sunset Amber 30%
- **Disabled**: Background #F8F9FA, Border #DEE2E6

**Label**: À direita, 16px Regular, Text Primary, padding-left 12px

---

#### Radio Button
**Aparência**:
- Size: 20x20px
- Border: 2px solid #ADB5BD
- Border Radius: 50%
- Background: White

**Estados**:
- **Selected**: Border 2px solid Sunset Amber, inner circle 10px Sunset Amber
- **Hover**: Border Sea Deep
- **Focus**: Outline 2px solid Sunset Amber 30%
- **Disabled**: Background #F8F9FA, Border #DEE2E6

**Label**: À direita, 16px Regular, padding-left 12px

---

#### Toggle / Switch
**Aparência**:
- Width: 48px
- Height: 28px
- Background: #CED4DA
- Border Radius: 14px
- Thumb: 20x20px circle, White, shadow suave

**Estados**:
- **On**: Background #52B788, thumb à direita
- **Off**: Background #CED4DA, thumb à esquerda
- **Hover**: Brightness aumentado
- **Focus**: Outline 2px solid da cor ativa
- **Disabled**: Background #E9ECEF, opacity 0.6

**Label**: À esquerda ou direita, 16px Medium

---

#### Slider
**Aparência**:
- Height: 4px (track)
- Background: #DEE2E6 (track)
- Border Radius: 2px
- Thumb: 24x24px circle, Sunset Amber, shadow
- Fill: Sunset Amber (parte preenchida)

**Estados**:
- **Hover**: Thumb scale(1.1)
- **Active**: Thumb scale(0.95)
- **Focus**: Thumb outline 2px solid Sunset Amber 50%
- **Disabled**: Grayscale, opacity 0.5

**Labels**: Min/Max valores nas extremidades

**Uso**: Escala de emoções (0-10), intensidade, configurações

---

### 5.2.4 Navegação

#### Bottom Navigation Bar (Mobile)
**Aparência**:
- Height: 64px
- Background: White
- Border Top: 1px solid #E9ECEF
- Shadow: 0 -2px 8px rgba(0,0,0,0.08)
- 4-5 itens máximo

**Item**:
- Icon: 24px
- Label: 11px Medium
- Active Color: Sunset Amber
- Inactive Color: #6C757D
- Padding: 8px

**Estados**:
- **Active**: Icon e Label em Sunset Amber, background sutil
- **Inactive**: Cor cinza
- **Tap**: Ripple effect suave

---

#### Tab Bar
**Aparência**:
- Height: 48px
- Border Bottom: 2px solid #E9ECEF
- Background: Transparent

**Tab Item**:
- Padding: 12px 20px
- Font: 16px Medium
- Indicator: 3px altura, Sunset Amber, abaixo do tab ativo

**Estados**:
- **Active**: Text Sunset Amber, indicator visível
- **Inactive**: Text #6C757D
- **Hover**: Text Sea Deep

---

#### Sidebar (Desktop)
**Aparência**:
- Width: 260px
- Background: White
- Border Right: 1px solid #E9ECEF
- Padding: 24px 16px

**Item**:
- Height: 44px
- Padding: 12px 16px
- Border Radius: 10px
- Icon: 20px à esquerda
- Label: 16px Regular

**Estados**:
- **Active**: Background Sunset Amber 10%, Text Sunset Amber, Icon Sunset Amber
- **Inactive**: Text Sea Deep
- **Hover**: Background #F8F9FA

---

### 5.2.5 Modais e Overlays

#### Modal
**Aparência**:
- Max Width: 500px (mobile: 90vw)
- Background: White
- Border Radius: 20px
- Padding: 32px
- Shadow: 0 8px 32px rgba(0,0,0,0.16)

**Overlay**:
- Background: rgba(26, 47, 61, 0.6)
- Blur: backdrop-filter: blur(4px) (se suportado)

**Header**:
- Icon opcional (48px)
- Título: H3 (24px Semi Bold)
- Close button: 40x40px, top-right

**Body**:
- Padding: 24px 0
- Max Height: 60vh (scroll se necessário)

**Footer**:
- Padding: 24px 0 0 0
- Botões alinhados à direita
- Espaçamento entre botões: 12px

---

#### Bottom Sheet (Mobile)
**Aparência**:
- Width: 100vw
- Border Radius: 20px 20px 0 0
- Background: White
- Padding: 24px
- Handle: 32px width, 4px height, #CED4DA, centralizado no topo

**Animação**: Slide up from bottom

**Uso**: Seleção de opções, filtros, formulários curtos

---

#### Toast / Snackbar
**Aparência**:
- Width: Max 400px (mobile: 90vw)
- Height: Auto (min 48px)
- Background: Sea Deep (#2A4858)
- Color: White
- Border Radius: 12px
- Padding: 12px 16px
- Shadow: 0 4px 16px rgba(0,0,0,0.24)
- Position: Bottom center, 24px do fundo

**Variações**:
- **Success**: Background #52B788
- **Warning**: Background #FFB703
- **Error**: Background #E63946
- **Info**: Background #457B9D

**Componentes**:
- Icon: 20px à esquerda (opcional)
- Message: 14px Regular
- Action Button: 14px Semi Bold (opcional)
- Close: 16x16px icon (opcional)

**Duração**: 4 segundos (ajustável)

---

### 5.2.6 Ícones

#### Biblioteca
**Selecionada**: Phosphor Icons (Open Source)
**Alternativa**: Heroicons

**Justificativa**:
- Estilo minimalista e amigável
- Múltiplas variações (regular, bold, fill, duotone)
- Excelente cobertura de ícones
- Otimizados para web

#### Tamanhos Padrão
- **Small**: 16px (uso em labels, badges)
- **Medium**: 20px (uso em botões, inputs)
- **Large**: 24px (navegação, FAB)
- **XLarge**: 32px (ilustrações, estados vazios)
- **2XLarge**: 48px (splash screens, onboarding)

#### Estilo
- **Stroke Width**: 1.5px (regular), 2px (bold)
- **Corners**: Rounded
- **Color**: Herda do contexto ou especificado

#### Ícones Principais do App
- **Diário**: Book / BookOpen
- **Exercícios**: Activity / Lightning
- **Humor**: Smiley / Heart
- **Tarefas**: CheckSquare / ListChecks
- **Perfil**: User / UserCircle
- **Configurações**: Gear / Sliders
- **Notificações**: Bell
- **Busca**: MagnifyingGlass
- **Adicionar**: Plus / PlusCircle
- **Deletar**: Trash
- **Editar**: PencilSimple / Pen
- **Compartilhar**: ShareNetwork / Export
- **Favorito**: Heart / Star
- **Calendário**: Calendar / CalendarBlank
- **Tempo**: Clock / Timer
- **Respiração**: Wind / Waves
- **Meditação**: Flower / Peace

---

### 5.2.7 Ilustrações

#### Estilo
**Conceito**: Ilustrações minimalistas, orgânicas, calmantes
**Paleta**: Cores do brand (Sunset, Sunrise, Sky, Sea, Earth)
**Traços**: Suaves, arredondados, sem cantos agressivos
**Elementos**: Formas abstratas, natureza, figuras humanas simplificadas

#### Contextos de Uso
1. **Onboarding**: 3-4 ilustrações explicando o app
2. **Estados Vazios**: Ilustrações gentis indicando ausência de conteúdo
3. **Erros**: Ilustrações reconfortantes para páginas de erro
4. **Conquistas**: Ilustrações celebratórias para milestones
5. **Exercícios**: Ilustrações representando cada tipo de prática

#### Tamanhos
- **Hero**: 400x300px (desktop), 300x225px (mobile)
- **Medium**: 200x150px
- **Small**: 100x75px

---

## 5.3 Layouts para Funcionalidades

### 5.3.1 Diário Emocional (5 variações)

**Layout 1: Lista Cronológica**
- Entradas em ordem reversa (mais recente primeiro)
- Cada entrada: Card com data, preview do texto (3 linhas), emoções marcadas (badges)
- FAB para nova entrada
- Scroll infinito

**Layout 2: Calendário Visual**
- Grid de calendário mensal
- Cada dia colorido pela emoção predominante
- Tap no dia abre modal com entradas daquele dia
- Navegação mês anterior/próximo

**Layout 3: Timeline com Linhas**
- Timeline vertical à esquerda
- Cards conectados por linhas
- Agrupamento por semana/mês
- Indicadores visuais de progresso

**Layout 4: Cards Grandes com Imagens**
- Cards grandes (full width)
- Opção de adicionar fotos
- Texto completo visível
- Espaçamento generoso

**Layout 5: Compacto com Filtros**
- Lista compacta (altura reduzida)
- Filtros por emoção no topo
- Tags clicáveis
- Busca integrada

---

### 5.3.2 Questionários (5 variações)

**Layout 1: Uma Pergunta por Tela**
- Pergunta em H2 no topo
- Opções de resposta espaçadas
- Progresso no topo (5/12)
- Botões "Voltar" e "Próxima"

**Layout 2: Scrollável Multi-pergunta**
- Múltiplas perguntas na mesma tela
- Scroll vertical
- Auto-save de respostas
- Botão "Concluir" no final

**Layout 3: Wizard com Steps**
- Indicador de steps horizontal no topo
- Cards por categoria de perguntas
- Transição suave entre steps
- Possibilidade de pular

**Layout 4: Conversacional**
- Interface tipo chat
- Perguntas aparecem como mensagens
- Respostas como botões ou input
- Fluxo natural e dinâmico

**Layout 5: Visual com Escalas**
- Perguntas com sliders visuais
- Escala 1-10 com ícones
- Feedback visual imediato
- Resultados em tempo real

---

### 5.3.3 Exercícios (5 variações)

**Layout 1: Biblioteca com Categorias**
- Grid de cards de exercícios
- Filtros por categoria (Respiração, Meditação, etc)
- Tags de duração (5min, 10min, 20min)
- Favoritos destacados

**Layout 2: Exercício em Andamento**
- Tela fullscreen
- Instruções centralizadas
- Timer circular no topo
- Botões "Pausar" e "Parar"
- Background com gradiente suave

**Layout 3: Lista de Progresso**
- Lista de exercícios com checkmarks
- Indicador de quantas vezes completado
- Streak contador (dias consecutivos)
- Botão "Continuar" ou "Começar"

**Layout 4: Recomendações Personalizadas**
- Cards grandes com ilustrações
- "Recomendado para você" baseado em histórico
- Carrossel horizontal
- Descrição expandida

**Layout 5: Sessão Guiada Interativa**
- Animações suaves (respiração, ondas)
- Áudio opcional
- Instruções passo-a-passo
- Vibração háptica (mobile)

---

### 5.3.4 Tarefas de Autocuidado (5 variações)

**Layout 1: Lista de Checklist Simples**
- Checkboxes à esquerda
- Tarefas com título e descrição curta
- Ordem customizável (drag & drop)
- Adicionar nova tarefa com FAB

**Layout 2: Kanban Board**
- Colunas: "A Fazer", "Em Andamento", "Concluído"
- Cards arrastáveis
- Contador de tarefas por coluna
- Filtros e busca

**Layout 3: Calendário de Hábitos**
- Grid semanal/mensal
- Cada célula representa um dia
- Check verde para concluído
- Padrões visuais de consistência

**Layout 4: Tarefas com Prioridade**
- Agrupamento por prioridade (Alta, Média, Baixa)
- Cores de categorização
- Data de vencimento visível
- Notificações integradas

**Layout 5: Gamificada com Pontos**
- Tarefas valem pontos
- Barra de progresso semanal/mensal
- Badges de conquistas
- Recompensas visuais

---

### 5.3.5 Resumos e Insights (5 variações)

**Layout 1: Dashboard com Cards**
- Grid de cards com métricas
- Gráficos pequenos (sparklines)
- Destaques coloridos
- Scroll vertical

**Layout 2: Gráficos Detalhados**
- Gráfico principal no topo (line chart de humor)
- Filtros de período (semana, mês, ano)
- Gráficos secundários abaixo (bar, pie)
- Exportar dados (CSV, PDF)

**Layout 3: Narrativo com Texto**
- Resumo em texto corrido
- "Nesta semana você..."
- Insights personalizados
- Comparação com períodos anteriores

**Layout 4: Visual Infográfico**
- Layout tipo infográfico
- Ícones grandes
- Números destacados
- Progressos percentuais
- Compartilhável como imagem

**Layout 5: Timeline de Progresso**
- Linha do tempo visual
- Marcos importantes destacados
- Evolução ao longo do tempo
- Anotações contextuais

---

## 5.4 Padrões de Microinteração

### 5.4.1 Feedback Visual

**Tap/Click**:
- Ripple effect suave (material design style)
- Cor: Sunset Amber com 20% opacidade
- Duração: 400ms

**Loading**:
- Spinner circular com gradiente
- Cores: Sunset Amber → Sunrise Gold
- Smooth rotation
- 32px size

**Success**:
- Checkmark animado (draw animation)
- Cor: #52B788
- Duração: 600ms
- Acompanhado de toast

**Error**:
- Shake animation suave
- 3 vibrações pequenas
- Duração: 500ms
- Borda vermelha temporária

---

### 5.4.2 Transições

**Fade In/Out**:
- Duração: 200ms
- Easing: ease-in-out
- Uso: Modais, tooltips

**Slide Up**:
- Duração: 300ms
- Easing: cubic-bezier(0.4, 0, 0.2, 1)
- Uso: Bottom sheets, toasts

**Scale**:
- Duração: 250ms
- From: scale(0.95) to scale(1)
- Uso: Modais, popups

**Page Transitions**:
- Duração: 350ms
- Slide horizontal para navegação principal
- Fade para mudanças de contexto

---

### 5.4.3 Estados de Progresso

**Barra de Progresso Linear**:
- Height: 4px
- Background: #E9ECEF
- Fill: Gradiente Sunset Amber → Sunrise Gold
- Border Radius: 2px
- Animação suave de preenchimento

**Progresso Circular**:
- Stroke Width: 6px
- Background: #E9ECEF
- Stroke: Gradiente circular
- Animação: Sentido horário
- Texto central: Percentual

**Step Indicator**:
- Círculos conectados por linhas
- Completo: Sunset Amber com check
- Atual: Borda Sunset Amber
- Futuro: Cinza claro

---

## 5.5 Acessibilidade de Componentes

### 5.5.1 Keyboard Navigation
- ✅ Tab order lógico
- ✅ Focus visible (outline)
- ✅ Enter para ativar botões
- ✅ Space para checkboxes
- ✅ Arrow keys em listas e selects
- ✅ Escape para fechar modais

### 5.5.2 Screen Readers
- ✅ Aria-labels descritivos
- ✅ Aria-live regions para atualizações
- ✅ Role attributes corretos
- ✅ Alt text em imagens
- ✅ Labels associados a inputs

### 5.5.3 Touch Targets
- ✅ Mínimo 44x44px (Apple HIG, WCAG)
- ✅ Espaçamento de 8px entre targets
- ✅ Feedback tátil (haptic) quando apropriado

---

## 5.6 Modo Escuro

Todos os componentes devem ter versões para modo escuro, seguindo as cores definidas na seção 3.4 do manual de cores.

**Ajustes Principais**:
- Inverter contraste texto/fundo
- Reduzir saturação de cores em 10-15%
- Ajustar shadows (menos intensas)
- Bordas mais sutis
- Manter acessibilidade de contraste

---

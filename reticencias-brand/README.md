# Projeto reticências - Identidade Visual Completa
## Aplicativo de Saúde Mental

![Status](https://img.shields.io/badge/Status-Completo-success)
![Versão](https://img.shields.io/badge/Versão-1.0-blue)
![Páginas](https://img.shields.io/badge/Páginas-85+-informational)

---

## 📖 Sobre o Projeto

Este repositório contém a **identidade visual completa** do aplicativo **reticências**, incluindo:

- ✅ Manual de marca com 85+ páginas
- ✅ 10 variações de símbolo da logomarca
- ✅ 15 composições de logomarca (5 horizontais, 5 verticais, 5 quadradas)
- ✅ Sistema de cores com 5 cores primárias + variações
- ✅ Sistema tipográfico completo
- ✅ Design system com 50+ componentes de UI
- ✅ 10 opções de slogan
- ✅ Guia completo de tom de voz
- ✅ 40+ prompts do Stable Diffusion para geração de assets
- ✅ Especificações para mockups e aplicações

---

## 🎨 Conceito da Marca

**reticências** é um aplicativo de saúde mental que utiliza o símbolo dos três pontos (...) como metáfora central:

- **Continuidade**: A jornada de saúde mental é contínua
- **Pausa reflexiva**: Momentos de respiração e reflexão
- **Possibilidades abertas**: O futuro está em construção
- **Transformação gradual**: Cada ponto representa um passo
- **Não-julgamento**: A história ainda está sendo escrita

---

## 📁 Estrutura do Repositório

```
reticencias-brand/
│
├── brand-manual/              # Manual de marca completo
│   ├── 00-INDEX.md           # Índice do manual
│   ├── 01-INTRODUCAO.md      # Introdução e conceito
│   ├── 02-LOGOMARCA.md       # Especificações da logomarca
│   ├── 03-CORES.md           # Sistema de cores
│   ├── 04-TIPOGRAFIA.md      # Sistema tipográfico
│   ├── 05-UI-ELEMENTOS.md    # Design system e componentes
│   ├── 06-IDENTIDADE-VERBAL.md  # Tom de voz e slogans
│   └── 07-APLICACOES-MOCKUPS.md # Aplicações e mockups
│
├── prompts/                   # Prompts para geração de assets
│   └── STABLE-DIFFUSION-PROMPTS.md
│
├── logos/                     # Logos gerados (criar)
├── color-system/              # Paletas de cores (criar)
├── typography/                # Fontes e exemplos (criar)
├── ui-components/             # Componentes de UI (criar)
├── slogans/                   # Opções de slogan (criar)
├── mockups/                   # Mockups em contexto (criar)
│
└── README.md                  # Este arquivo
```

---

## 🎯 Guia Rápido de Uso

### Para Designers

1. **Consulte o manual**: Comece pelo `00-INDEX.md` para visão geral
2. **Logomarca**: `02-LOGOMARCA.md` - 10 variações do símbolo
3. **Cores**: `03-CORES.md` - Paleta completa com HEX, RGB, CMYK
4. **UI**: `05-UI-ELEMENTOS.md` - Design system completo
5. **Gere assets**: Use os prompts em `prompts/STABLE-DIFFUSION-PROMPTS.md`

### Para Desenvolvedores

1. **Sistema de cores**: Tokens CSS em `03-CORES.md` (seção 3.8)
2. **Tipografia**: Classes CSS em `04-TIPOGRAFIA.md` (seção 4.9)
3. **Componentes**: Especificações em `05-UI-ELEMENTOS.md`
4. **Acessibilidade**: Diretrizes em todas as seções (WCAG AAA)

### Para Redatores

1. **Tom de voz**: `06-IDENTIDADE-VERBAL.md` (seção 6.2)
2. **Slogans**: 10 opções na seção 6.1
3. **Glossário**: Termos preferidos na seção 6.4
4. **Microcopy**: Exemplos na seção 6.6

### Para Marketing

1. **Aplicações**: `07-APLICACOES-MOCKUPS.md` - Todos os contextos
2. **Redes sociais**: Seção 7.2.6
3. **Materiais impressos**: Seção 7.3
4. **Mockups**: Seção 7.5

---

## 🌈 Paleta de Cores Principal

| Cor | Nome | HEX | RGB | Uso Principal |
|-----|------|-----|-----|---------------|
| 🧡 | Sunset Amber | `#F4A261` | 244, 162, 97 | Botões, CTAs, destaques |
| 💛 | Sunrise Gold | `#E9C46A` | 233, 196, 106 | Progresso, conquistas |
| 💙 | Sky Calm | `#94C5CC` | 148, 197, 204 | Fundos, mindfulness |
| 💙 | Sea Deep | `#2A4858` | 42, 72, 88 | Texto principal, navegação |
| 💚 | Earth Soft | `#A8DADC` | 168, 218, 220 | Sucesso, equilíbrio |

---

## ✍️ Tipografia

**Fonte Principal**: [Inter](https://rsms.me/inter/)  
**Pesos utilizados**: Light (300), Regular (400), Medium (500), Semi Bold (600), Bold (700)  
**Características**: Humanista, excelente legibilidade digital, open source

---

## 💬 Slogans (Top 3)

1. **"Cada ponto, um passo. Cada pausa, um recomeço."** ⭐ Recomendado
2. **"Sua jornada interior tem espaço para respirar..."**
3. **"Transformação gradual, cuidado diário."**

Ver todas as 10 opções em `06-IDENTIDADE-VERBAL.md`

---

## 🚀 Como Gerar Assets Visuais

Este projeto usa **Stable Diffusion** para gerar elementos visuais. Siga os passos:

### Passo 1: Configure o Stable Diffusion
```bash
# Já está configurado neste repositório stable-diffusion-webui
# Navegue até a interface web do Stable Diffusion
```

### Passo 2: Use os Prompts
1. Abra `prompts/STABLE-DIFFUSION-PROMPTS.md`
2. Escolha o asset que deseja gerar (logo, ilustração, ícone, etc.)
3. Copie o prompt correspondente
4. Cole no campo de prompt do Stable Diffusion
5. Configure parâmetros recomendados
6. Gere!

### Passo 3: Pós-processamento
- Use **Real-ESRGAN** para upscaling de logos
- Vetorize logos no Adobe Illustrator
- Ajuste cores para match exato com o brand
- Salve em múltiplos formatos (AI, EPS, SVG, PNG)

---

## 📐 Especificações Técnicas

### Logos
- **Formatos**: AI, EPS, SVG, PNG
- **Resoluções PNG**: 16px, 32px, 64px, 128px, 256px, 512px, 1024px, 2048px, 4096px
- **Área de proteção**: 1x altura do símbolo
- **Tamanho mínimo**: 48x48px (digital), 15x15mm (impresso)

### Cores
- **Modo digital**: RGB, HEX
- **Modo impresso**: CMYK, Pantone
- **Acessibilidade**: WCAG AAA compliance
- **Modo escuro**: Paleta ajustada disponível

### Tipografia
- **Mobile**: 12-32px
- **Desktop**: 14-48px
- **Line height**: 1.25-1.6x
- **Max line width**: 75 caracteres

---

## ✅ Checklist de Implementação

### Fase 1: Assets Básicos
- [ ] Gerar 10 variações do símbolo
- [ ] Criar 15 composições de logomarca
- [ ] Exportar todos os formatos e tamanhos
- [ ] Criar app icons (iOS e Android)
- [ ] Gerar splash screens

### Fase 2: Design System
- [ ] Implementar sistema de cores (CSS variables)
- [ ] Configurar tipografia (web fonts)
- [ ] Criar biblioteca de componentes (Figma)
- [ ] Desenvolver ícones customizados
- [ ] Gerar ilustrações principais

### Fase 3: Conteúdo
- [ ] Finalizar slogan oficial
- [ ] Criar banco de microcopy
- [ ] Desenvolver templates de comunicação
- [ ] Revisar tom de voz em textos existentes

### Fase 4: Marketing
- [ ] Criar website/landing page
- [ ] Desenvolver assets para redes sociais
- [ ] Produzir screenshots para app stores
- [ ] Criar materiais impressos
- [ ] Gerar mockups de contexto real

---

## 🎓 Princípios da Marca

### Design
- **Minimalismo**: Menos é mais, clareza visual
- **Suavidade**: Cantos arredondados, transições suaves
- **Acessibilidade**: WCAG AAA, inclusive para todos
- **Calma**: Cores suaves, espaçamento generoso

### Tom de Voz
- **Acolhedor**: Linguagem calorosa, não infantilizada
- **Não-julgador**: Respeito a todas as experiências
- **Encorajador**: Celebração de pequenas vitórias
- **Baseado em evidências**: Ciência, não pseudociência

---

## 📱 Aplicações

O manual cobre aplicações em:

**Digital**:
- App iOS e Android
- Website / Landing page
- Email marketing
- Redes sociais (Instagram, Facebook, LinkedIn, Twitter)
- Anúncios digitais

**Impresso**:
- Cartão de visita
- Papel timbrado
- Apresentações
- Folhetos e flyers
- Posters e banners

**Promocional**:
- Camisetas
- Canecas
- Adesivos
- Cadernos/Diários

---

## 🔒 Licença e Uso

Este projeto é **propriedade do reticências** e está protegido por direitos autorais.

### Uso Autorizado
✅ Equipe interna do projeto  
✅ Parceiros oficiais (com autorização)  
✅ Freelancers/agências contratados (com NDA)

### Uso Não Autorizado
❌ Reprodução sem autorização  
❌ Modificação sem aprovação  
❌ Uso comercial não relacionado

---

## 📚 Recursos e Referências

### Ferramentas Recomendadas
- **Design**: Figma, Sketch, Adobe Illustrator, Photoshop
- **Geração de Assets**: Stable Diffusion, DALL-E
- **Tipografia**: Google Fonts, Adobe Fonts
- **Ícones**: Phosphor Icons, Heroicons
- **Mockups**: Canva, Placeit, Smartmockups

### Links Úteis
- [Inter Font](https://rsms.me/inter/)
- [Phosphor Icons](https://phosphoricons.com/)
- [WCAG Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)
- [Color Contrast Checker](https://webaim.org/resources/contrastchecker/)

---

## 📞 Suporte e Contato

Para dúvidas, sugestões ou solicitações:

**Email**: brand@reticencias.app  
**Website**: www.reticencias.app  
**Documentação**: docs.reticencias.app

---

## 🎉 Agradecimentos

Este manual de marca foi desenvolvido com atenção aos detalhes, foco em acessibilidade e compromisso com a missão do **reticências**: tornar o autocuidado em saúde mental acessível, acolhedor e baseado em evidências.

---

## 📊 Estatísticas do Projeto

- **Total de Páginas do Manual**: 85+
- **Variações de Logo**: 25 (10 símbolos + 15 composições)
- **Cores na Paleta**: 20+ (5 primárias + variações)
- **Componentes de UI**: 50+
- **Layouts de Funcionalidade**: 25
- **Opções de Slogan**: 10
- **Prompts de Stable Diffusion**: 40+
- **Aplicações Documentadas**: 30+

---

**Versão**: 1.0  
**Data**: Fevereiro 2026  
**Status**: ✅ Completo e pronto para implementação

---

**Desenvolvido com 💙 para o projeto reticências**

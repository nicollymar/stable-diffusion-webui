# Prompts do Stable Diffusion para Geração de Assets - reticências

Este documento contém todos os prompts otimizados para gerar os elementos visuais do aplicativo **reticências** usando Stable Diffusion.

---

## Como Usar Este Documento

1. Copie o prompt desejado
2. Cole no Stable Diffusion WebUI (campo de prompt)
3. Use os parâmetros recomendados (CFG Scale, Steps, Sampler)
4. Ajuste o negative prompt conforme necessário
5. Gere múltiplas variações (batch) para escolher a melhor

---

## Configurações Recomendadas

**Modelo**: Stable Diffusion v2.1 ou superior  
**Sampler**: DPM++ 2M Karras ou Euler a  
**Steps**: 30-50  
**CFG Scale**: 7-9  
**Resolution**: Conforme especificado em cada prompt  

**Negative Prompt Padrão**:
```
ugly, deformed, distorted, low quality, blurry, pixelated, noise, watermark, text, signature, aggressive, harsh, clinical, cold, medical equipment, hospitals, needles, pills
```

---

## 1. Logos e Símbolos

### 1.1 Logo Versão 1: Três Círculos Progressivos

**Prompt**:
```
minimalist logo design, three circles gradually increasing in size from left to right, clean geometric shapes, modern minimal design, vector style, flat design, mental health app icon, soft rounded shapes, professional branding, on white background, high contrast, perfect circles, simple and elegant, progression concept, growth symbolism, #F4A261 sunset amber color, pastel color palette, mental wellness theme
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Minimalist, geometric
- Formato: Square

---

### 1.2 Logo Versão 2: Pontos em Trajetória Ascendente

**Prompt**:
```
minimalist logo icon, three dots in ascending diagonal line, upward movement, clean vector style, flat design, mental health brand, simple geometric shapes, hope and progress concept, soft rounded dots, #F4A261 amber and #E9C46A gold gradient, modern app icon design, white background, professional, elegant, inspirational symbolism
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Vector, flat

---

### 1.3 Logo Versão 3: Círculos Interconectados

**Prompt**:
```
minimalist logo design, three overlapping circles forming venn diagram, subtle intersection areas, connection concept, holistic wellness symbol, clean vector style, soft pastel colors (#94C5CC sky blue, #A8DADC earth soft, #F4A261 sunset amber), modern mental health app branding, white background, professional design, interconnected elements, unity symbolism
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Overlapping shapes, soft

---

### 1.4 Logo Versão 4: Pontos com Respiração

**Prompt**:
```
minimalist logo icon, three circles with subtle wave lines emanating outward, breathing concept visualization, mindfulness symbol, clean vector art, soft curved lines, calming design, #94C5CC sky calm blue color, white background, modern mental wellness app logo, meditation and breath work theme, gentle flowing lines, serene and peaceful aesthetic
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Organic, flowing

---

### 1.5 Logo Versão 5: Minimalista Linear

**Prompt**:
```
ultra minimalist logo, three simple dots in horizontal line, clean and simple, perfect circles, equal spacing, monochrome or #2A4858 sea deep blue, white background, extreme minimalism, professional app icon, clarity and simplicity concept, modern tech branding, geometric precision, tiny icon optimized design, 16x16px scalable
```

**Parâmetros**:
- Resolução: 1024x1024 (depois redimensionar)
- Estilo: Ultra minimal

---

### 1.6 Logo Versão 6: Orgânico Natural

**Prompt**:
```
organic minimalist logo, three soft rounded shapes resembling smooth pebbles or water drops, natural forms, hand-crafted aesthetic, gentle curves, earthy colors (#A8DADC, #94C5CC, #E9C46A), nature-inspired mental health branding, calming organic shapes, white background, approachable and warm design, natural wellness concept, fluid forms
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Organic, hand-drawn feel

---

### 1.7 Logo Versão 7: Pontos em Onda

**Prompt**:
```
minimalist logo design, three dots arranged in smooth wave curve pattern, flowing wave concept, emotional journey symbolism, clean vector style, dynamic yet calm composition, #2A4858 sea deep blue and #94C5CC sky calm gradient, white background, modern app branding, ups and downs of mental health journey, gentle undulating line, balanced composition
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Wave, dynamic

---

### 1.8 Logo Versão 8: Círculos Concêntricos

**Prompt**:
```
minimalist logo icon, three circles each composed of concentric rings, depth and layers concept, consciousness levels symbolism, clean geometric design, #F4A261 sunset amber with varying opacity, white background, modern mental wellness app, introspection theme, nested circles, sophisticated and contemplative design, mindfulness layers
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Layered, depth

---

### 1.9 Logo Versão 9: Pontos com Gradiente

**Prompt**:
```
minimalist gradient logo, three circles with smooth color transition, gradient from #E9C46A sunrise gold to #F4A261 sunset amber to #94C5CC sky calm, transformation concept, modern app icon design, clean vector style, white background, professional mental health branding, gradual change symbolism, smooth color blend, contemporary aesthetic
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Gradient, smooth

---

### 1.10 Logo Versão 10: Pontos Vazados (Anéis)

**Prompt**:
```
minimalist logo design, three ring shapes with transparent centers, hollow circles, outline style icon, negative space design, introspection concept, clean line art, #2A4858 sea deep blue outlines, white background, modern mental wellness app, inner space symbolism, simple elegant rings, contemplative design, circular frames
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Outline, negative space

---

## 2. Ilustrações para o App

### 2.1 Onboarding Ilustração 1: Boas-vindas

**Prompt**:
```
calm welcoming illustration, person meditating in peaceful environment, soft pastel colors (#F4A261, #E9C46A, #94C5CC, #A8DADC), minimalist flat design illustration, mental health app onboarding screen, gentle abstract shapes in background, warm and inviting atmosphere, simple character design, no faces or minimal facial features, modern illustration style, cozy and safe feeling, sunrise or sunset colors
```

**Parâmetros**:
- Resolução: 1080x1920 (vertical mobile)
- Estilo: Flat illustration

---

### 2.2 Onboarding Ilustração 2: Recursos do App

**Prompt**:
```
flat design illustration showing app features, smartphone with abstract UI elements, journal icon, exercise icon, mood tracking visualization, clean minimalist illustration, mental wellness theme, pastel color palette (#F4A261 sunset amber, #94C5CC sky calm, #E9C46A sunrise gold), modern tech illustration, friendly and approachable style, simple iconography, organized composition
```

**Parâmetros**:
- Resolução: 1080x1920
- Estilo: Flat, UI-focused

---

### 2.3 Onboarding Ilustração 3: Progresso e Crescimento

**Prompt**:
```
growth concept illustration, abstract plant or tree growing, upward progress visualization, minimalist flat design, mental health journey metaphor, soft organic shapes, pastel colors (#A8DADC earth soft, #E9C46A sunrise gold), simple and hopeful illustration, personal development theme, clean composition, modern app illustration style, inspirational and encouraging mood
```

**Parâmetros**:
- Resolução: 1080x1920
- Estilo: Organic, growth

---

### 2.4 Estado Vazio: Diário Sem Entradas

**Prompt**:
```
gentle empty state illustration, closed or open journal book, minimalist design, soft colors, welcoming atmosphere, #E9C46A sunrise gold and #94C5CC sky calm palette, simple flat illustration, mental health journaling app, calm and inviting mood, clean composition, encouraging aesthetic, no text elements, space for writing concept, serene environment
```

**Parâmetros**:
- Resolução: 800x600
- Estilo: Simple, inviting

---

### 2.5 Estado Vazio: Nenhum Exercício

**Prompt**:
```
empty state illustration, person sitting in meditation pose or yoga position, soft minimalist style, calm environment, pastel color scheme (#94C5CC sky calm, #A8DADC earth soft), flat design illustration, mental wellness exercises concept, peaceful and serene mood, simple character without detailed face, encouraging atmosphere, clean background
```

**Parâmetros**:
- Resolução: 800x600
- Estilo: Calm, minimal

---

### 2.6 Erro 404: Página Não Encontrada

**Prompt**:
```
friendly error page illustration, person looking confused but not distressed, searching concept, soft and reassuring design, pastel colors (#F4A261, #94C5CC), minimalist flat illustration, mental health app aesthetic, gentle and non-alarming mood, simple character design, modern illustration style, lost but not anxious feeling, compassionate design
```

**Parâmetros**:
- Resolução: 800x600
- Estilo: Friendly, soft

---

### 2.7 Conquista: Milestone Completado

**Prompt**:
```
celebration illustration, abstract confetti or sparkles, achievement concept, joyful but calm design, gradient colors (#E9C46A to #F4A261), minimalist celebratory illustration, mental health app success screen, encouraging and positive mood, simple geometric shapes, modern flat style, uplifting but not overwhelming, gentle celebration aesthetic
```

**Parâmetros**:
- Resolução: 800x800
- Estilo: Celebratory, abstract

---

### 2.8 Exercício: Respiração

**Prompt**:
```
breathing exercise illustration, abstract visualization of breath flow, expanding and contracting circles or lungs, calming blue colors (#94C5CC sky calm, #A8DADC earth soft), minimalist design, mindfulness meditation concept, soft flowing lines, gentle wave patterns, serene and peaceful mood, modern mental wellness illustration, rhythmic visual concept
```

**Parâmetros**:
- Resolução: 1080x1080
- Estilo: Abstract, flowing

---

### 2.9 Exercício: Meditação

**Prompt**:
```
meditation illustration, person in lotus position silhouette, abstract peaceful environment, minimalist design, soft pastel colors (#94C5CC, #A8DADC, white), clean flat illustration, mental wellness app, serene and tranquil atmosphere, simple character design, modern mindfulness aesthetic, calm composition, zen-like simplicity
```

**Parâmetros**:
- Resolução: 1080x1080
- Estilo: Zen, minimal

---

### 2.10 Exercício: Journaling

**Prompt**:
```
journaling illustration, hand writing in notebook or digital device, reflection concept, soft warm colors (#E9C46A sunrise gold, #F4A261 sunset amber), minimalist flat design, mental health diary theme, contemplative mood, simple illustration style, personal reflection visualization, cozy and intimate feeling, modern app illustration
```

**Parâmetros**:
- Resolução: 1080x1080
- Estilo: Cozy, personal

---

## 3. Backgrounds e Texturas

### 3.1 Background: Pôr do Sol

**Prompt**:
```
abstract sunset gradient background, soft blend from #E9C46A sunrise gold to #F4A261 sunset amber to soft pink, minimal geometric shapes, calm and peaceful atmosphere, mental health app background, smooth color transitions, modern digital wallpaper, serene mood, no harsh elements, gentle warm tones, contemplative aesthetic
```

**Parâmetros**:
- Resolução: 1920x1080 (desktop) ou 1080x1920 (mobile)
- Estilo: Gradient, abstract

---

### 3.2 Background: Amanhecer

**Prompt**:
```
abstract sunrise gradient, soft blend from deep #2A4858 sea deep blue to #94C5CC sky calm to #E9C46A sunrise gold, hope and new beginnings concept, clean gradient background, mental wellness app wallpaper, peaceful morning atmosphere, smooth color transition, modern minimalist design, uplifting mood
```

**Parâmetros**:
- Resolução: 1920x1080 ou 1080x1920
- Estilo: Gradient, uplifting

---

### 3.3 Background: Céu Tranquilo

**Prompt**:
```
abstract sky background, soft blue tones (#94C5CC sky calm, #A8DADC earth soft), subtle cloud-like shapes, calming atmosphere, mental health app background, gentle gradients, serene sky concept, minimalist design, peaceful and open feeling, clean composition, modern app wallpaper, tranquil mood
```

**Parâmetros**:
- Resolução: 1920x1080 ou 1080x1920
- Estilo: Sky, calm

---

### 3.4 Background: Mar Profundo

**Prompt**:
```
abstract ocean depth background, gradient from #2A4858 sea deep blue to darker tones, subtle wave patterns, contemplative and introspective mood, mental wellness app background, deep water concept, calming yet profound atmosphere, minimalist water texture, modern design, mysterious but safe feeling, depth visualization
```

**Parâmetros**:
- Resolução: 1920x1080 ou 1080x1920
- Estilo: Depth, water

---

### 3.5 Background: Terra e Natureza

**Prompt**:
```
abstract nature background, soft green and blue tones (#A8DADC earth soft, #94C5CC), organic shapes, natural textures, earthy calming palette, mental health app wallpaper, grounding concept, gentle nature-inspired design, minimalist organic patterns, peaceful and balanced mood, modern natural aesthetic
```

**Parâmetros**:
- Resolução: 1920x1080 ou 1080x1920
- Estilo: Nature, organic

---

## 4. Ícones Customizados

### 4.1 Ícone: Diário/Journal

**Prompt**:
```
minimalist icon of an open book or journal, simple line art, clean design, mental health journaling symbol, #2A4858 sea deep blue color, white background, 256x256px icon, modern flat icon style, clear and recognizable, app icon design, personal diary concept
```

**Parâmetros**:
- Resolução: 1024x1024 (redimensionar para 256x256)
- Estilo: Line icon

---

### 4.2 Ícone: Exercícios/Activity

**Prompt**:
```
minimalist activity icon, abstract person in motion or lightning bolt, energy symbol, simple line art, #F4A261 sunset amber color, white background, 256x256px app icon, modern flat design, clear and bold, mental wellness exercises symbol, dynamic but calm
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Dynamic icon

---

### 4.3 Ícone: Humor/Mood

**Prompt**:
```
minimalist mood icon, simple smiley face or heart shape, emotion tracking symbol, clean line art, #E9C46A sunrise gold color, white background, 256x256px icon, modern app icon design, friendly and approachable, mental health mood tracking, gentle and soft design
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Friendly icon

---

### 4.4 Ícone: Respiração/Breath

**Prompt**:
```
minimalist breathing icon, abstract wind or wave symbol, breath flow visualization, simple line art, #94C5CC sky calm blue color, white background, 256x256px icon, modern mindfulness app, clean and flowing design, meditation and breathing exercises symbol
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Flowing icon

---

### 4.5 Ícone: Conquistas/Achievements

**Prompt**:
```
minimalist achievement icon, simple trophy or star or medal, success symbol, clean line art, #52B788 success green color, white background, 256x256px app icon, modern flat design, celebratory but understated, mental health milestones symbol
```

**Parâmetros**:
- Resolução: 1024x1024
- Estilo: Achievement icon

---

## 5. Padrões e Texturas

### 5.1 Padrão: Pontos (Reticências)

**Prompt**:
```
seamless pattern of three dots repeated, minimalist dotted pattern, subtle and elegant, mental health brand pattern, pastel colors (#F4A261, #E9C46A, #94C5CC) on white or light background, clean geometric repeat pattern, modern design texture, brand identity pattern, simple and sophisticated
```

**Parâmetros**:
- Resolução: 512x512 (tileable)
- Estilo: Pattern, seamless

---

### 5.2 Padrão: Ondas Orgânicas

**Prompt**:
```
seamless pattern of gentle wave lines, organic flowing curves, calming water-inspired pattern, soft blue and green tones (#94C5CC, #A8DADC), minimalist design, mental wellness brand texture, subtle repetitive pattern, modern and serene, tileable seamless pattern
```

**Parâmetros**:
- Resolução: 512x512 (tileable)
- Estilo: Organic pattern

---

### 5.3 Textura: Papel Suave

**Prompt**:
```
subtle paper texture, soft and gentle surface, minimal grain, warm white or cream color, high resolution texture, mental health app background texture, not distracting, clean and professional, slight texture for depth, modern digital paper feel
```

**Parâmetros**:
- Resolução: 2048x2048
- Estilo: Texture, subtle

---

## 6. Mockup Scenes

### 6.1 Mockup: Pessoa Usando App no Café

**Prompt**:
```
lifestyle photography mockup, person holding smartphone showing mental health app interface, sitting in cozy cafe, natural window light, warm atmosphere, soft focus background, modern casual setting, hands holding phone in foreground, app screen clearly visible, calm and peaceful moment, realistic photography style, coffee cup nearby, plants in background
```

**Parâmetros**:
- Resolução: 1920x1280
- Estilo: Photography, lifestyle

**Note**: Para este tipo de mockup, pode ser mais eficaz usar fotografias reais e sobrepor as telas do app em edição.

---

### 6.2 Mockup: Workspace com Laptop

**Prompt**:
```
clean workspace photography, laptop on wooden desk showing mental health app website, natural daylight, minimalist office setup, small plant nearby, organized and calm environment, realistic photography, professional and serene atmosphere, soft shadows, modern workspace aesthetic, mental wellness branding context
```

**Parâmetros**:
- Resolução: 1920x1280
- Estilo: Photography, workspace

---

### 6.3 Mockup: Materiais de Marca Flat Lay

**Prompt**:
```
flat lay photography, mental health app branding materials on white background, business cards, flyers, notebook, mug with logo, arranged aesthetically, top-down view, natural soft lighting, subtle shadows, clean composition, brand identity showcase, professional flat lay styling, pastel color accents matching brand colors
```

**Parâmetros**:
- Resolução: 1920x1280
- Estilo: Photography, flat lay

---

## 7. Social Media Assets

### 7.1 Instagram Post: Quote

**Prompt**:
```
instagram post design, mental health motivational quote on calm gradient background (#94C5CC to white), minimalist typography, "Pause. Breathe. Continue." text, small reticencias logo in corner, clean modern design, square format, serene and uplifting mood, professional social media graphic, mental wellness theme
```

**Parâmetros**:
- Resolução: 1080x1080
- Estilo: Social media graphic

---

### 7.2 Instagram Story: Tip

**Prompt**:
```
instagram story design, mental health tip with simple illustration, vertical format, soft pastel background (#F4A261 sunset amber gradient), clean typography, minimal decorative elements, small breathing exercise icon, modern app branding, friendly and informative style, story template design
```

**Parâmetros**:
- Resolução: 1080x1920
- Estilo: Story template

---

## 8. Configurações Adicionais

### Upscaling
Para logos e ícones que precisam de altíssima resolução:
- Use **Real-ESRGAN** ou **ESRGAN** para upscale
- 2x ou 4x upscaling
- Mantenha sharpness adequada

### Inpainting
Para ajustar elementos específicos:
- Use inpainting para corrigir detalhes
- Mantenha o mask preciso
- Use prompts específicos para a área

### Variações
- Gere 4-9 imagens por prompt
- Escolha as melhores
- Combine elementos de diferentes gerações

---

## Dicas Gerais

1. **Seja específico**: Quanto mais detalhado o prompt, melhor o resultado
2. **Use cores HEX**: Mencione as cores específicas do brand
3. **Negative prompts**: Sempre use para evitar elementos indesejados
4. **Iterate**: Gere múltiplas versões e refine
5. **Post-processing**: Use edição de imagem para ajustes finais
6. **Consistência**: Use mesmos parâmetros para assets relacionados
7. **Teste resolução**: Gere em alta resolução e redimensione se necessário

---

## Ferramentas Complementares

- **Adobe Illustrator**: Para vetorizar logos gerados
- **Figma**: Para criar layouts de UI com assets gerados
- **Photoshop**: Para composições e ajustes finais
- **Canva**: Para templates de social media rápidos
- **Remove.bg**: Para remover backgrounds de ilustrações

---

**Fim do Documento de Prompts**

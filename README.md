# 🎨 Art Code Experiment

Repositório para experimentação com arte generativa e creative coding na web. Uma coleção interativa de visualizações artísticas programáticas, cada uma explorando diferentes técnicas e bibliotecas.

## ✨ Destaques

- 🎭 **5 visualizações interativas** completas e customizáveis
- 🎨 **35+ paletas de cores** diferentes entre todos os projetos
- 🎛️ **Controles em tempo real** para todas as visualizações
- 📸 **Captura de tela** em todos os projetos
- 📱 **Responsivo** - funciona em desktop e mobile
- ⚡ **Performance otimizada** com milhares de partículas

## 🚀 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/tremedam/Art_Code_Experiment.git
```

2. Abra o arquivo `index.html` em seu navegador
3. Explore os diferentes exemplos!

> Não é necessário instalação ou servidor - funciona direto no navegador! 🎉

## 📁 Estrutura do Projeto

```
Art_Code_Experiment/
├── index.html              # Página principal com galeria moderna
├── examples/
│   ├── p5js-particles/     # Sistema de partículas com 6 comportamentos
│   ├── canvas-generative/  # Arte generativa com 10 padrões
│   ├── threejs-3d/         # Galáxia 3D com 4 tipos
│   │   ├── index.html      # Galáxia 3D
│   │   └── mao.html        # Mão 3D articulada
│   └── p5js-fractal/       # Árvore fractal com temas sazonais
├── README.md
└── LICENSE
```

## 🛠️ Tecnologias Utilizadas

- **p5.js v1.7.0** - Biblioteca para creative coding e visualizações 2D
- **Three.js r128** - Biblioteca para gráficos e renderização 3D com WebGL
- **Canvas API** - API nativa do HTML5 para desenho 2D
- **JavaScript ES6+** - Linguagem de programação moderna
- **CSS3** - Glass-morphism, backdrop-filter, animações

## 💡 Exemplos Incluídos

### 1. ✨ Partículas Interativas (p5.js)

Sistema avançado de partículas com física realista e múltiplos comportamentos.

**Recursos:**
- **6 Comportamentos:** Atrair, Repelir, Orbitar, Explodir, Onda, Enxame
- **7 Paletas de Cores:** Arco-íris, Oceano, Fogo, Neon, Roxo, Verde, Monocromático
- **Controles Avançados:**
  - Densidade de partículas (10-200)
  - Tamanho (1-10px)
  - Velocidade (0.1x-5x)
  - Distância de conexão (0-200px)
  - Força de atração/repulsão (0-5)
  - Comprimento da trilha (0-50)
- **Efeitos Visuais:** Brilho (glow), pulso, conexões dinâmicas
- **Estatísticas:** FPS e contagem de partículas em tempo real

### 2. 🎭 Arte Generativa (Canvas API)

Gerador de padrões geométricos com controle total sobre complexidade e estilo.

**10 Padrões Incluídos:**
- Círculos concêntricos
- Triângulos aleatórios
- Quadrados em grade
- Spirograph animado
- Mandala rotativa
- Flow Field (Perlin Noise)
- Fractais recursivos
- Ondas senoidais
- Ruído visual
- Sistema de partículas

**8 Paletas de Cores:**
- Pastel, Vibrante, Monocromático, Arco-íris, Oceano, Fogo, Terra, Neon

**Controles:**
- Complexidade (1-20)
- Densidade (1-100)
- Tamanho (0.5x-3x)
- Animação (ativa/desativa para padrões compatíveis)

### 3. 🌌 Galáxia 3D (Three.js)

Simulação de galáxias com diferentes morfologias e controle orbital.

**4 Tipos de Galáxia:**
- 🌀 **Espiral:** Galáxia clássica com braços espirais
- ⭕ **Elíptica:** Distribuição esférica uniforme
- 💍 **Anel:** Galáxia em forma de anel
- 🌟 **Irregular:** Distribuição caótica com clusters

**7 Paletas de Cores:**
- Clássico (azul-laranja)
- Fogo (vermelho-amarelo)
- Oceano (ciano-azul)
- Neon (magenta-ciano)
- Roxo (rosa-roxo)
- Verde (verde brilhante)
- Dourado (amarelo-laranja)

**Controles Completos:**
- Partículas: 1.000 - 50.000
- Braços: 2-8
- Spin: 0-3
- Dispersão: 0-2
- Tamanho das partículas: 0.005-0.05
- Velocidade de rotação: 0-5x
- Auto-rotação (liga/desliga)
- Randomizar tudo
- Screenshot em alta qualidade

**Interação:**
- Arraste para rotacionar a câmera orbitalmente
- Scroll para zoom (1-30 unidades)
- Inércia suave

### 4. ✋ Mão 3D (Three.js)

Modelo 3D articulado de uma mão com controle individual de cada dedo.

**6 Temas Visuais:**
- 👤 Humano (rosa natural)
- 🤖 Robô (metálico com emissão azul)
- 👽 Alienígena (verde brilhante)
- 👻 Fantasma (azul translúcido)
- 🧟 Zumbi (verde apodrecido)
- ⭐ Dourado (ouro metálico)

**8 Gestos Prontos:**
- ✋ Abrir - ✊ Fechar
- ✌️ Paz - 👍 Positivo
- 👌 OK - 🤘 Rock
- 🤙 Shaka - ☝️ Um

**Controles Individuais:**
- Sliders para cada um dos 4 dedos (0-100%)
- Controle do polegar (0-100%)
- Controle preciso de cada falange

**Animações:**
- 👋 Acenar
- 🥁 Tamborilar
- 🌊 Ondular

**Efeitos:**
- Inércia dos dedos ao rotacionar
- Sombras suaves em tempo real
- Iluminação em 3 pontos
- Velocidade de animação ajustável (0.1x-3x)

### 5. 🌳 Árvore Fractal (p5.js)

Geração recursiva de árvores fractais com temas sazonais e decorações.

**6 Temas Sazonais:**
- 🌸 Primavera (rosa, flores)
- ☀️ Verão (verde vibrante, folhas)
- 🍂 Outono (laranja-vermelho, folhas caindo)
- ❄️ Inverno (azul-branco, flocos de neve)
- 🌸 Sakura (rosa japonês, pétalas)
- 🌙 Noite (roxo-azul escuro, estrelas)

**Controles Avançados:**
- Ângulo dos galhos (0-90°)
- Profundidade/Níveis (1-12)
- Assimetria (0-50%)
- Fator de redução (0.5-0.9)

**Decorações:**
- Flores (primavera/sakura)
- Folhas (verão/outono)
- Flocos de neve (inverno)
- Estrelas (noite)
- Efeito de vento suave

**Recursos:**
- Geração aleatória
- Salvar como imagem
- Atualização em tempo real

## 📚 Recursos para Aprender

### Documentação Oficial
- [p5.js Reference](https://p5js.org/reference/) - Documentação completa do p5.js
- [Three.js Documentation](https://threejs.org/docs/) - Guia oficial do Three.js
- [Canvas API MDN](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) - Referência da Canvas API

### Tutoriais e Cursos
- [The Coding Train (YouTube)](https://www.youtube.com/c/TheCodingTrain) - Daniel Shiffman
- [Generative Artistry](https://generativeartistry.com/) - Tutoriais de arte generativa
- [Three.js Journey](https://threejs-journey.com/) - Curso completo de Three.js
- [Creative Coding](https://www.youtube.com/c/CreativeCodingwithKCC) - Tutoriais práticos

### Inspiração
- [OpenProcessing](https://openprocessing.org/) - Galeria de sketches p5.js
- [Shadertoy](https://www.shadertoy.com/) - Shaders e arte visual
- [CodePen](https://codepen.io/tag/generative-art) - Exemplos de arte generativa

## 🎯 Roadmap Futuro

Ideias para expandir o projeto:

### Novas Visualizações
- [ ] Visualizador de áudio com FFT
- [ ] Autômatos celulares (Conway's Game of Life)
- [ ] L-Systems avançados
- [ ] Simulação de fluidos
- [ ] Raymarching com shaders

### Melhorias Técnicas
- [ ] Implementar shaders GLSL customizados
- [ ] Adicionar suporte a VR/WebXR
- [ ] Criar API para integração externa
- [ ] Performance profiling e otimizações
- [ ] Exportação de vídeo (WebM/MP4)

### Features Gerais
- [ ] Sistema de presets/favoritos com localStorage
- [ ] Compartilhamento de configurações via URL
- [ ] Modo escuro/claro
- [ ] Internacionalização (i18n)
- [ ] Tutorial interativo para iniciantes

## 🤝 Contribuindo

Contribuições são muito bem-vindas! Sinta-se livre para:

1. Fazer fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Add: MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

### Sugestões de Contribuição
- Adicionar novos padrões generativos
- Criar novas paletas de cores
- Melhorar a performance
- Adicionar novos comportamentos de partículas
- Corrigir bugs
- Melhorar a documentação

## 📝 Licença

MIT License - sinta-se livre para usar, modificar e distribuir!

## 🎨 Galeria de Screenshots

Visite a [página principal](https://tremedam.github.io/Art_Code_Experiment/) para ver as visualizações ao vivo!

---

**Feito com ❤️ para aprender e compartilhar conhecimento sobre creative coding**

🌟 Se você gostou do projeto, considere dar uma estrela no GitHub!

## 📬 Contato

- GitHub: [@tremedam](https://github.com/tremedam)
- Projeto: [Art Code Experiment](https://github.com/tremedam/Art_Code_Experiment)

---

*"A arte é a mentira que nos permite conhecer a verdade."* - Pablo Picasso

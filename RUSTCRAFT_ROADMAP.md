# RustCraft — Plano de desenvolvimento

RustCraft é um projeto derivado de VoxeLibre, baseado no motor Luanti. O objetivo é manter a experiência sandbox voxel de sobrevivência e construção, criar uma identidade própria e adicionar modos de jogo originais.

## Princípios
- Android como plataforma prioritária; Windows depois.
- Preservar a jogabilidade base enquanto as mudanças são testadas.
- Fazer alterações incrementais, com commits pequenos e reversíveis.
- Não remover créditos, avisos de licença ou atribuições de conteúdo.
- Não anunciar recursos como concluídos até serem implementados e testados em jogo.

## Linha de versões Alpha

### 0.1.0-alpha — Fundação e identidade
- [x] Nome do jogo no catálogo: RustCraft.
- [x] Descrição inicial própria.
- [x] Branch de desenvolvimento separada da branch master.
- [ ] Ícone, logo e arte de menu próprios.
- [ ] Revisão dos créditos e avisos para a distribuição RustCraft.

### 0.2.0-alpha — Interface e experiência mobile
- [ ] Revisar HUD, hotbar, inventário e telas de crafting.
- [ ] Definir tema visual RustCraft (azul profundo, ardósia e laranja).
- [ ] Ajustar escala, toque e posicionamento dos controles Android.
- [ ] Testar em diferentes resoluções e proporções de tela.

### 0.3.0-alpha — Conteúdo visual
- [ ] Criar pacote visual original para blocos, itens e interface.
- [ ] Criar sons e efeitos próprios quando necessário.
- [ ] Manter um inventário de autoria e licenças de cada recurso.
- [ ] Verificar legibilidade e desempenho no celular.

### 0.4.0-alpha — Mundo e desempenho
- [ ] Revisar geração de terreno, biomas e estruturas.
- [ ] Adicionar opções de desempenho para aparelhos modestos.
- [ ] Testar carregamento de chunks, partículas e distância de visão.
- [ ] Validar criação, salvamento e reabertura de mundos.

### 0.5.0-alpha — SkyBlock
- [ ] Criar modo SkyBlock com geração inicial própria.
- [ ] Definir progressão, desafios e recompensas.
- [ ] Garantir isolamento das regras do modo normal.
- [ ] Testar mundos novos e salvamento.

### 0.6.0-alpha — Battle Royale
- [ ] Criar arena e fluxo de partida.
- [ ] Implementar loot, zona segura e eliminação.
- [ ] Adicionar construção de paredes/barricadas durante a partida.
- [ ] Testar multiplayer, balanceamento e desempenho.

### 0.7.0-alpha — FPS
- [ ] Criar modo de partida separado do survival.
- [ ] Implementar armas voxel originais, munição e recarga.
- [ ] Criar mapas, equipes e regras.
- [ ] Testar controles mobile e multiplayer.

### 0.8.0-alpha — Aventura e acabamento
- [ ] Criar objetivos, estruturas e progressão de aventura.
- [ ] Polir áudio, efeitos, menus e tutoriais.
- [ ] Corrigir bugs encontrados nos testes.
- [ ] Preparar builds Android de teste.

## Critérios para cada Alpha
Uma versão só será marcada como pronta quando:
1. O código compilar/carregar sem erros conhecidos introduzidos pela versão.
2. O recurso principal estiver implementado.
3. A criação e o salvamento de mundos forem testados.
4. Os controles Android forem verificados em aparelho real.
5. As licenças e créditos dos arquivos incluídos estiverem documentados.

## Base e licenças
RustCraft parte do código do VoxeLibre. O código-base é distribuído sob GPL-3.0-or-later, salvo indicação diferente em componentes específicos. Mídias podem ter licenças próprias, incluindo CC BY-SA e CC BY-SA 4.0. Verifique os avisos de cada arquivo/mod antes de redistribuir. Preserve os créditos, licenças e o código-fonte correspondente exigido pela licença aplicável.

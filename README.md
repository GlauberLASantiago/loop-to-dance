# 🩰 Loop to Dance

Aplicativo web para prática de dança com vídeo. Permite carregar vídeos locais, marcar trechos (loops), treinar repetindo os loops selecionados e controlar velocidade e zoom — tudo no navegador, sem instalar nada.

## ✨ Funcionalidades

- **Carregamento de vídeo local** — selecione qualquer vídeo do seu dispositivo
- **Histórico de vídeos** — acesse rapidamente vídeos já utilizados (com miniatura e duração)
- **Marcação manual** — marque pontos no vídeo para criar loops com início e fim definidos
- **Marcação automática (🎵 Auto)** — detecta automaticamente transientes de áudio para sugerir marcações no ritmo da música
- **Treino por loops** — selecione um ou mais loops e entre no modo treino para repeti-los em sequência
- **Controle de velocidade** — ajuste a velocidade de reprodução de 0.25x a 2.00x
- **Zoom e pan** — amplie o vídeo e navegue com arraste (suporte a pinça em dispositivos touch)
- **PWA** — pode ser adicionado à tela inicial como um app

## 🚀 Como usar

1. Acesse o app pelo navegador (ou adicione à tela inicial para usar como PWA)
2. Toque em **Selecionar Vídeo** e escolha um arquivo de vídeo do seu dispositivo
3. Reproduza o vídeo e use o botão **📍 Marcar** para adicionar pontos de marcação
   - Ou use o botão **🎵 Auto** para detecção automática pelo ritmo do áudio
4. Os pares de marcações formam loops que aparecem na lista
5. Selecione os loops desejados e clique em **Treinar** para repetir os trechos
6. Use os sliders de **Velocidade** e **Zoom** conforme necessário

## 🛠️ Tecnologias

- HTML5, CSS3, JavaScript puro (sem frameworks)
- Web Audio API (análise de transientes para marcação automática)
- LocalStorage (histórico e dados dos vídeos)
- Service Worker / PWA

## 📱 Compatibilidade

Funciona em navegadores modernos, incluindo Chrome e Safari em dispositivos móveis (Android e iOS).

## 📂 Estrutura

```
loop-to-dance/
└── index.html   # Aplicação completa (single-file)
```

# Zorka UIKIT

Design System oficial da **Zorka** — sistema de gestão para lojas e oficinas de bike.

Estrutura espelhada do UIKIT da Takeat: um manifesto (`design-system.json`) que aponta para tokens e componentes, todos consumíveis por IA via `raw.githubusercontent.com`.

## Estrutura

```
design-system.json        ← manifesto (comece por aqui)
tokens/
  colors.json             ← paletas 100→700 (vermelho Zorka, funcionais, neutros, superfícies dark)
  typography.json         ← escala Inter (Display, Kicker, Title, Body, Label, Details)
  spacing.json            ← escala de espaçamento (2→48px)
  radius.json             ← raios (sm→2xl + pill)
  shadows.json            ← elevação 01→05 + hero
components/
  uikit-ai.json           ← catálogo de 48 componentes com variantes/estados
```

## Identidade em resumo

- **Dark-first** — fundo `#0E1016`, cards `#161A22` com borda `rgba(255,255,255,.12)`
- **Vermelho Zorka** `#E42525` (soft `#EE3B3B`) — único acento de marca
- **Tipografia forte** — Inter 700/800, tracking negativo em títulos; kickers uppercase com tracking `0.28em` e ponto vermelho
- **Assinaturas** — textura de grid sutil no fundo, chips pill, underline vermelho grosso em palavras-chave, screenshots com raio 24px e sombra profunda

## Prompt para desenvolvimento com IA

```
Utilize exclusivamente o Design System oficial da Zorka como referência de
identidade visual. Considere como fonte única o arquivo:
https://raw.githubusercontent.com/AGothe07/zorka-uikit/main/design-system.json
Não utilize estilos genéricos, Material Design, Apple Human Interface
Guidelines ou qualquer outro Design System. Todas as decisões visuais devem
seguir as definições presentes nesse arquivo e na documentação referenciada
por ele.
```

# Zorka UIKIT

Design System oficial da **Zorka** — sistema de gestão para lojas e oficinas de bike.

> **v2.0.0:** a identidade visual da Zorka agora é **idêntica ao Design System oficial da Takeat**. Os tokens deste repositório são cópias fiéis do [takeat-design/UIKIT](https://github.com/takeat-design/UIKIT) — mesma fonte (Poppins), mesmo vermelho (#C8131B), mesmos neutros, radius e sombras usados no dashboard Takeat e no agente SDR.

Estrutura: um manifesto (`design-system.json`) que aponta para tokens e componentes, todos consumíveis por IA via `raw.githubusercontent.com`.

## Estrutura

```
design-system.json        ← manifesto (comece por aqui)
tokens/
  colors.json             ← paletas 100→700 (vermelho Takeat, funcionais, neutros puros)
  typography.json         ← escala Poppins (Title, Body, Label, Details)
  spacing.json            ← escala de espaçamento (2→48px)
  radius.json             ← raios (sm 4px, md 8px, lg 12px, xl 16px)
  shadows.json            ← elevação 01→05 (02 é o padrão)
components/
  uikit-ai.json           ← catálogo de componentes com variantes/estados
```

## Identidade em resumo

- **Light-first** — fundo branco, texto `#222222` (neutral.500); dark mode derivado do `#222222`, nunca preto puro em áreas grandes
- **Vermelho Takeat** `#C8131B` (red.500; hover/glow `#D13F45`) — único acento de marca
- **Tipografia Poppins** 400–800 — escala Title/Body/Label/Details da Takeat
- **Neutros puros** `#F6F6F6 / #EDEDED / #C6C6C6 / #7A7A7A / #545454 / #222222` — sem cinzas azulados
- **Radius** 4/8/12/16px · **Sombras** elevação 01–05 (02 padrão)
- Contraste: para TEXTO sobre branco use `red.500+`, `yellow.600+`, `blue.600+`

## Prompt para desenvolvimento com IA

```
Utilize exclusivamente o Design System oficial da Zorka como referência de
identidade visual. Considere como fonte única o arquivo:
https://raw.githubusercontent.com/AGothe07/zorka-uikit/main/design-system.json
(identidade idêntica ao Design System Takeat desde a v2.0.0).
Não utilize estilos genéricos, Material Design, Apple Human Interface
Guidelines ou qualquer outro Design System. Todas as decisões visuais devem
seguir as definições presentes nesse arquivo e na documentação referenciada
por ele.
```

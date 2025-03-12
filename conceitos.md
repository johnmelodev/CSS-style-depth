**Resumo do Capítulo 2: Unidades Relativas no CSS**

- **Unidades relativas**: Adaptam-se ao contexto (ex.: `em`, `rem`, `%`, `vw`, `vh`).
- **Ems (`em`)**: Baseiam-se no tamanho da fonte do elemento atual ou herdado.

  - Para `font-size`: Usa o tamanho herdado.
  - Para outras propriedades: Usa o tamanho local.
  - Problema: Encolhimento de texto em listas aninhadas.
    - Solução: Use `1em` para listas dentro de listas.

- **Rems (`rem`)**: Baseiam-se no tamanho da fonte do elemento raiz (`<html>`).

  - Evita problemas de composição de `ems`.

- **Viewport units**:

  - `vw`: 1% da largura da viewport.
  - `vh`: 1% da altura da viewport.

- **Vantagens das unidades relativas**:
  - Responsividade: Adaptação a diferentes telas.
  - Escalabilidade: Facilidade para ajustes globais.
  - Acessibilidade: Melhor suporte ao zoom e preferências do usuário.

Dica: Use `ems` para ajustes locais e `rems` para valores globais.

# Intervalos

Plugin para o **MuseScore Studio 4** que analisa exercícios de contraponto e
escreve na partitura os **intervalos harmônicos entre as vozes**, abaixo de
cada pauta. Funciona com 2 ou mais vozes.

**Versão atual:** 0.23 · [Histórico de versões](CHANGELOG.md) · Licença [GPL-3.0](LICENSE)

![Exemplo de intervalos escritos pelo plugin em um contraponto a 4 vozes](docs/exemplo.png)

*Exemplo a 4 vozes (imagem de uma versão anterior: a partir da v0.21.1 os
rótulos "(1 e 2):" deixaram de ser escritos).*

## Notação

- Números indicam o intervalo simples (`U` = uníssono, `2` a `8`).
- Cada apóstrofo indica uma oitava a mais: `3'` = 10ª, `5''` = 5ª + duas oitavas.
- `d` indica intervalo diminuto (ex.: `5d`).

## Instalação

1. Baixe o plugin: clique em **Code ▸ Download ZIP** nesta página (ou baixe
   uma versão específica na aba **Tags**).
2. Descompacte e copie a pasta **`Intervalos`** inteira (com o
   `Intervalos.qml` e o `Intervalos.png`) para a pasta de plugins do MuseScore:
   - **Windows:** `Documentos\MuseScore4\Plugins\`
   - **macOS:** `~/Documents/MuseScore4/Plugins/`
   - **Linux:** `~/Documentos/MuseScore4/Plugins/` (ou `~/Documents/MuseScore4/Plugins/`)

   A pasta exata pode ser conferida em **Editar ▸ Preferências ▸ Pastas ▸ Plugins**.
3. No MuseScore, abra **Plugins ▸ Gerenciar plugins**, encontre
   **Intervalos** e clique em **Ativar**.
4. O plugin passa a aparecer em **Plugins ▸ Contraponto ▸ Intervalos**.

## Como usar

1. Escreva o contraponto na partitura, uma voz por pauta.
2. Opcionalmente, selecione o trecho ou as pautas desejadas. Sem seleção, a
   partitura inteira é analisada.
3. Execute **Plugins ▸ Contraponto ▸ Intervalos**. Os intervalos são
   escritos como texto de pauta e podem ser apagados ou editados normalmente
   (**Ctrl+Z** desfaz).

## Versões anteriores

- **MuseScore 4.0 a 4.3 e MuseScore 3:** use a tag [`v0.22`](../../tree/v0.22).
- **MuseScore 3 (versão de manutenção):** tag [`v0.21.1-ms3`](../../tree/v0.21.1-ms3),
  arquivo `musescore3/Intervalos.qml`.
- **MuseScore 2:** tag [`v0.21-ms2`](../../tree/v0.21-ms2), arquivo
  `musescore2/Intervalos.qml`.

## Plugins relacionados

- [Analisador de Contrapontos](https://github.com/rogerioConstante/analisador-de-contrapontos):
  verifica condução de vozes, melodia e tratamento de dissonâncias em
  exercícios de contraponto.

## Autor

Rogério Tavares Constante. Desenvolvido no âmbito do projeto
*Harmonia e Contraponto*.

Sugestões e relatos de problemas são bem-vindos na aba **Issues**.

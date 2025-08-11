# Changelog
Todas as mudanças notáveis neste projeto serão documentadas aqui.

---

## [2.1.6] - 11/08/2025
### Correções
- Inclusão completa de dependências no pacote (`vscode-nls`, `iconv-lite`, `safer-buffer`), eliminando erros de *"Cannot find module"*.
- Ajustes no `.vscodeignore` para manter apenas arquivos necessários no pacote final.
- Testes de instalação confirmados sem erros no VS Code.

---

## [2.1.5] - 10/08/2025
### Adicionado
- Sistema de mensagens multi-idiomas (i18n) usando `vscode-nls`.
- Detecção de compilador `pawncc` aprimorada para suportar mais cenários.

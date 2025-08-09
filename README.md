# PawnPro

Extensão moderna e segura para desenvolvimento em **Pawn** no Visual Studio Code.  
Oferece ferramentas práticas para diagnóstico, compilação e produtividade no seu fluxo de trabalho.

## Recursos
- **Diagnóstico de `#include`**  
  Identifica e marca includes inexistentes ou inválidos no código.  
- **Compilação rápida**  
  Comando `Pawn: Compilar arquivo atual` diretamente no VS Code.  
- **Configuração flexível**  
  Ajuste caminhos de includes, parâmetros e localização do compilador.  
- **Compatibilidade**  
  Suporte a `.pwn` e `.inc`, com realce de sintaxe.

## Configuração
Em **Configurações** do VS Code, personalize:
- `pawn.includePaths` — caminhos adicionais para arquivos `.inc`.
- `pawn.compiler.path` — caminho do executável `pawncc`.
- `pawn.compiler.args` — argumentos passados ao compilador.
- `pawn.compiler.autoDetect` — ativar ou desativar detecção automática do compilador.
- `pawn.output.encoding` — escolha entre `utf8` ou `windows1252`.

## Dicas
- Garanta que `pawncc` esteja instalado e seja executável no caminho configurado.  
- Use aspas em caminhos com espaços para evitar erros.  
- Combine com extensões de destaque de sintaxe para uma experiência completa.

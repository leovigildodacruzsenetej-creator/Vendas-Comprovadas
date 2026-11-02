# Vendas-Comprovadas

Base inicial do repositório, organizada para evoluir de forma simples e gradual.

## Estado

Este repositório contém apenas documentação, convenções de edição e pastas de preparação. As funcionalidades, a linguagem, as dependências e a infraestrutura ainda serão definidas. Não há aplicação executável, processo de build ou testes automatizados nesta fase.

## Estrutura

| Caminho | Finalidade |
| --- | --- |
| `docs/` | Documentação e registo de decisões |
| `src/` | Código-fonte futuro |
| `tests/` | Testes futuros |
| `scripts/` | Utilitários de desenvolvimento futuros |
| `.editorconfig` | Convenções básicas de edição |
| `.gitignore` | Exclusões de ficheiros locais e potencialmente sensíveis |

Os ficheiros `.gitkeep` apenas mantêm pastas vazias no Git e podem ser removidos quando estas receberem conteúdo.

## Começar

1. Clonar o repositório:

   ```sh
   git clone https://github.com/leovigildodacruzsenetej-creator/Vendas-Comprovadas.git
   cd Vendas-Comprovadas
   ```

2. Consultar as [issues](https://github.com/leovigildodacruzsenetej-creator/Vendas-Comprovadas/issues) e escolher um próximo passo.
3. Criar uma branch para a alteração: `git switch -c chore/nome-da-alteracao`.
4. Fazer alterações pequenas e abrir um pull request com objetivo, validação e limitações.

Não é necessário instalar dependências para consultar esta base. Após a escolha da tecnologia, documentar aqui os requisitos e comandos reais de execução, build e testes.

## Configuração e segurança

O ficheiro `.editorconfig` define UTF-8, finais de linha LF, indentação de dois espaços e uma linha final. Estas opções são ajustáveis à tecnologia escolhida.

Não publicar palavras-passe, tokens, chaves privadas, ficheiros `.env` ou dados pessoais. A `.gitignore` é uma ajuda e não substitui a revisão do que será enviado. Se forem necessárias variáveis de ambiente, documentar apenas os nomes e exemplos fictícios num `.env.example`.

## Alterações e reversão

A inicialização está separada em dois commits: apresentação no README e estrutura/configuração. Cada etapa pode ser revertida pelo respetivo SHA com `git revert <SHA>`, começando pela mais recente caso se pretenda desfazer toda a base. Isto preserva o histórico; as issues são geridas separadamente e podem ser fechadas.

Antes de cada envio, rever `git diff --check`, `git diff --cached` e `git status`. Testes e outras verificações serão definidos quando existir código.

## Licença

A licença ainda não foi escolhida. Registar essa decisão antes de distribuir o projeto com termos de reutilização.

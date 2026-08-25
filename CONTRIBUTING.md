# CONTRIBUTING.md

##  Guia de Contribuição

Este documento apresenta as convenções que devem ser seguidas pelos integrantes da equipe durante o desenvolvimento do projeto **EventFy**.

O objetivo é manter o repositório organizado e facilitar a colaboração entre todos os membros da equipe.

---

##  Convenção para Branches

Cada nova alteração deve ser desenvolvida em uma branch específica.

O padrão para os nomes das branches será:

```text
tipo/descricao-da-alteracao
```

### Regras

* Utilizar apenas letras minúsculas;
* Separar as palavras utilizando hífen (`-`);
* Utilizar nomes curtos e descritivos;
* Não realizar alterações diretamente na branch `main`;
* Cada branch deve representar uma funcionalidade, correção ou alteração específica.

### Tipos de Branches

| Tipo        | Descrição                                  | Exemplo                             |
| ----------- | ------------------------------------------ | ----------------------------------- |
| `feature/`  | Desenvolvimento de uma nova funcionalidade | `feature/criar-evento`              |
| `fix/`      | Correção de erros                          | `fix/erro-login`                    |
| `docs/`     | Alterações na documentação                 | `docs/atualizar-readme`             |
| `test/`     | Criação ou alteração de testes             | `test/testes-cadastro`              |
| `chore/`    | Configurações e tarefas de manutenção      | `chore/atualizar-dependencias`      |
| `refactor/` | Refatoração de código                      | `refactor/organizar-codigo-eventos` |
| `ui/`       | Alterações relacionadas à interface        | `ui/tela-login`                     |
| `database/` | Alterações no banco de dados               | `database/criar-tabela-eventos`     |

### Exemplos

```text
feature/cadastro-usuario
feature/login-usuario
feature/criar-evento
feature/editar-evento
feature/excluir-evento
feature/inscricao-evento

fix/erro-login
fix/validacao-cadastro

docs/readme
docs/contributing

test/testes-login

chore/configuracao-inicial

refactor/organizar-codigo-eventos

ui/tela-cadastro

database/criar-tabela-eventos
```

---

##  Pull Requests

Após finalizar uma alteração, o integrante deve enviar as modificações para o repositório e abrir um **Pull Request**.

Antes de criar o Pull Request, é importante verificar se:

* A funcionalidade foi desenvolvida na branch correta;
* O código está funcionando corretamente;
* As alterações realizadas estão relacionadas ao objetivo da branch;
* A branch está atualizada com as alterações necessárias do projeto.

O Pull Request deve possuir um título claro e uma descrição explicando as alterações realizadas.

### Exemplo

**Título:**

```text
Implementa funcionalidade de criação de eventos
```

**Descrição:**

```text
## Descrição

Implementação da funcionalidade responsável pelo cadastro de novos eventos.

## Alterações realizadas

- Criação da estrutura do evento;
- Implementação do formulário de cadastro;
- Validação dos campos obrigatórios.
```

---

##  Revisão de Código

Todo Pull Request deverá ser revisado por outro integrante da equipe antes de ser aprovado.

O revisor deverá analisar as alterações e, quando necessário, deixar comentários ou sugestões de melhoria.

A aprovação do Pull Request só deve ocorrer após a revisão do código por pelo menos outro membro da equipe.

---

##  Branch `main`

A branch `main` representa a versão principal e estável do projeto.

Por esse motivo:

* Não devem ser realizados commits diretamente na `main`;
* Alterações devem ser desenvolvidas em branches específicas;
* A integração com a `main` deve ocorrer por meio de Pull Request;
* Todo Pull Request deve passar por revisão antes de ser integrado.

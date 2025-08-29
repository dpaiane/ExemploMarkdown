# Um titulo
## Outro título
### Outro título

Esse parágrafo uso **negrito** e *itálico* usando asteriscos

Para adicionar listas ordenadas use:
1. HTML
2. CSS
3. Javascript

Para adicionar listas não ordenadas use:
- HTML
- CSS
- Javascript

Para adicionar link use:
[tesxto do link](www.google.com.br)

Pra colocar imagens
![Desccrição da imagem](https://picsum.photos/id/237/200/300)

Para exemplos de código:
```
 int number = 10; 
 number += 1;     
 printf(Number);
```
Funcionalidades adicionais (específicas do GitHub)
Além do Markdown básico, o GitHub aceita alguns recursos que são muito úteis para um README:

Tabelas: Permitem organizar dados de forma estruturada. A sintaxe é um pouco mais complexa, mas muito útil.
A tabela Markdown usa barras verticais (|) para separar as colunas e hifens (-) para a linha de cabeçalho.

| Coluna 1         | Coluna 2         |
| --------------   | --------------   |
| Conteúdo linha 1 | Conteúdo linha 1 |
| Conteúdo linha 2 | Conteúdo linha 2 |

<details>
<summary>Minha tabela</summary>

| Comando      | Descrição                           |
| ------------ | ----------------------------------- |
| `git status` | Lista todos os arquivos modificados |
| `git diff`   | Mostra diferenças entre arquivos    |

</details>

Emojis: Você pode adicionar emojis usando a sintaxe :nome_do_emoji:, por exemplo, :rocket:.

Checkboxes (Tarefas): Crie listas de tarefas interativas.
- [x] Tarefa concluída
- [ ] Tarefa pendente

Badges: São pequenas imagens que mostram o status do seu projeto (por exemplo, build passing, versão 1.0.0). Muitos serviços, como Travis CI ou Shields.io, fornecem o código Markdown para você.

# Nome do Projeto

![Badge de Cobertura de Código](https://img.shields.io/coveralls/github/user/repo.svg)
![Badge de Versão](https://img.shields.io/npm/v/nomedopacote.svg)
![Badge de Licença](https://img.shields.io/github/license/user/repo.svg)

---

## Descrição do Projeto

Este é um projeto de exemplo para demonstrar o uso de badges em um arquivo README. Ele é um template simples, mas pode ser expandido para se adequar a qualquer tipo de projeto.

## Instalação

```bash
# Clone o repositório
git clone [https://github.com/user/repo.git](https://github.com/user/repo.git)

# Acesse o diretório do projeto
cd nome-do-projeto

# Instale as dependências (exemplo para Node.js)
npm install

Sintaxe para matemática: O GitHub também suporta renderização de equações matemáticas usando MathJax. Você precisa de um $  para equações em linha ou $$ para blocos de equações.

**Dicas finais**
Nome do arquivo: Garanta que seja README.md com o .md no final e o README em maiúsculas (ou minúsculas, mas README.md é o padrão).

Estrutura: Um bom README geralmente começa com um título e uma breve descrição do projeto. Em seguida, ele pode incluir seções como "Como usar", "Instalação", "Pré-requisitos", "Licença", e "Contribuições".

Objetivo: O principal objetivo do seu README é ser a página inicial do seu projeto, explicando de forma clara e concisa o que ele faz, como usá-lo e como as pessoas podem contribuir.

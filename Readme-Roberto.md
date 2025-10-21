# Cerebro da biblioteca
## Cerebro da biblioteca
### Cerebro da biblioteca
#### Cerebro da biblioteca

Um sistema desenvolvido para facilitar o **controle de livros**, **empréstimos** e **cadastro de alunos e professores** em uma biblioteca escolar.  
Seu principal objetivo é automatizar processos e reduzir erros manuais.

---

##  Índice
- [Funcionalidades](#funcionalidades)
- [Tecnologias](#tecnologias)
- [Como-usar](#como-usar)
- [Código-de-Exemplo](#exemplo)
- [Próximas-Atualizações](#próximas-atualizações)
- [Contribuidores](#contribuidores)
- [Contato](#contatos)

---

##  Funcionalidades
- Cadastro de livros, alunos e professores  
- Controle de empréstimos e devoluções  
- Geração de relatórios automáticos  
- Busca rápida de títulos e autores  
- Interface simples e responsiva  

---

##  Tecnologias

| Categoria | Tecnologia Utilizada |
|:---|:---:|
| Linguagem de Programação | Python  |
| Banco de Dados           | MySQL  |
| Framework                | Flask  |
| Sistema Operacional      | Windows / Linux  |

---

##  Como usar

1. **Baixe o projeto**
   - Faça o download do repositório clicando em **Code → Download ZIP** ou clone com o comando:
     ```bash
     https://github.com/rviniciusso/Atividade-Markdown-Roberto/edit/main/Readme-Roberto.md
     ```

2. **Extraia ou acesse a pasta**
   - Caso tenha baixado o ZIP, extraia os arquivos.
   - Caso tenha clonado, entre na pasta do projeto:
     ```bash
     cd sistema-biblioteca
     ```

---
### Cerebro da biblioteca
![Logo do Projeto](https://static.vecteezy.com/system/resources/previews/000/660/248/non_2x/education-book-logo-vector.jpg)
# Exemplo
## O nosso projeto segue esse código de _**exemplo**_

```python

from biblioteca import Biblioteca

biblioteca = Biblioteca()

biblioteca.cadastrar_livro("Dom Casmurro", "Machado de Assis")
biblioteca.cadastrar_livro("O Pequeno Príncipe", "Antoine de Saint-Exupéry")

biblioteca.emprestar_livro("Maria", "Dom Casmurro")

biblioteca.listar_livros_disponiveis()

biblioteca.devolver_livro("Maria", "Dom Casmurro")
```
---
 **Objetivos do Projeto:**
> O *Sistema de Gerenciamento de Biblioteca Escolar* tem como objetivo principal **automatizar o controle de livros, empréstimos e devoluções**, promovendo uma gestão **mais eficiente**, **organizada** e **acessível** para toda a comunidade escolar.

---

## Próximas Atualizações

- [ ] Implementar autenticação de usuários (login e senha)
- [ ] Criar módulo de relatórios em PDF
- [ ] Adicionar sistema de notificações por e-mail
- [ ] Melhorar o design da interface com novas cores e ícones
- [x] Corrigir erros no cadastro de livros
- [x] Otimizar a busca por título e autor

---

## Repositórios relacionados

> https://github.com/Sabrinagodoy12/Parcial-Programacion-UTN

> https://github.com/vnschneider/ml_kit_showcase_app

---
## Contribuidores
```
Agradecimentos para (@usuario1, @usuario2) que me ajudaram a realizar este incrivel feito de orgarnizar todo o sistema da blibioteca de uma forma tâo simples e bela
```
---
## Contatos 
- Entre em contato para dúvidas ou colaborações:
  - email@escola.com
  - (xx) xxxxx-xxxx

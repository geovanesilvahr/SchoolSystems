# SchoolSystem

## Descrição
SchoolSystem é um sistema escolar simples que permite o cadastro e gerenciamento de Alunos, Professores, Turmas e Matérias. O objetivo do projeto é para estudo e experiência de desenvolvimento de uma aplicação básica para administração escolar utilizando tecnologias modernas.

## Tecnologias Utilizadas
- **Linguagem:** Python
- **Framework:** Django
- **Banco de Dados:** SQLite3
- **Front-end:** Bootstrap

## Funcionalidades
- Cadastro, edição e remoção de Alunos
- Cadastro, edição e remoção de Professores
- Criação e gerenciamento de Turmas
- Cadastro e associação de Matérias
- Interface responsiva utilizando Bootstrap

## Requisitos
- Python 3.x
- Django
- SQLite3

## Como Executar o Projeto

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/SchoolSystem.git
cd SchoolSystem

# Crie e ative um ambiente virtual (opcional, mas recomendado)
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows

# Instale as dependências
pip install -r requirements.txt

# Execute as migrações do banco de dados
python manage.py migrate

# Inicie o servidor de desenvolvimento
python manage.py runserver
```

Acesse o sistema no navegador: [http://127.0.0.1:8000](http://127.0.0.1:8000)

## Estrutura do Projeto

```
SchoolSystem/
│-- manage.py
│-- db.sqlite3
│-- requirements.txt
│-- .gitignore
│-- apps/
│   │-- alunos/
│   │-- professores/
│   │-- turmas/
│   │-- materias/
│-- templates/
│-- static/
```

## Contribuição
Contribuições são bem-vindas! Para contribuir:

```bash
# Fork o repositório
# Crie uma branch
git checkout -b minha-feature

# Commit suas modificações
git commit -m 'Adicionando nova funcionalidade'

# Envie para o repositório remoto
git push origin minha-feature
```

Depois, abra um Pull Request.

---

## Autores

- [@geovanesilvahr](https://github.com/geovanesilvahr) 🚀

# Clínica Django

Aplicação web desenvolvida para gerenciamento de clínicas, com foco em organização de dados, estrutura backend sólida e aplicação de boas práticas com Django.

A proposta do projeto é centralizar informações clínicas em um sistema seguro, escalável e preparado para evolução.

---

## Funcionalidades

* Estrutura base para gerenciamento de dados clínicos
* Modelagem de entidades utilizando o ORM do Django
* Separação organizada entre regras de negócio e camadas da aplicação
* Base preparada para autenticação e controle de usuários
* Arquitetura pensada para expansão futura

---

## Tecnologias Utilizadas

* **Python** — lógica e regras do sistema
* **Django** — framework web e arquitetura MTV
* **SQLite** — banco de dados para desenvolvimento

---

## Como rodar o projeto

```bash
# Clone o repositório
git clone https://github.com/camilla-uchoa/Clinica-Django

# Acesse a pasta
cd Clinica-Django

# Crie um ambiente virtual
python -m venv venv

# Ative o ambiente virtual
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate

# Instale as dependências
pip install -r requirements.txt

# Rode as migrações
python manage.py migrate

# Execute o servidor
python manage.py runserver
```

---

## Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de praticar e consolidar conhecimentos em desenvolvimento backend com Django, incluindo:

* Estruturação de aplicações web escaláveis
* Modelagem de banco de dados com ORM
* Organização de código seguindo boas práticas
* Preparação para sistemas com autenticação e múltiplos usuários

---

## Status do Projeto

Em desenvolvimento

Atualmente o projeto está em fase de protótipo, com foco na construção da base estrutural. Novas funcionalidades serão adicionadas conforme a evolução do sistema.

---

## Melhorias Futuras

* [ ] Implementar sistema completo de autenticação
* [ ] Cadastro e gestão de pacientes
* [ ] Agendamento de consultas
* [ ] Painel administrativo mais intuitivo
* [ ] Integração com APIs externas
* [ ] Deploy em ambiente de produção

---

## Contribuição

Contribuições são bem-vindas!
Sinta-se à vontade para abrir issues ou enviar pull requests.

---

## Licença

Este projeto está sob a licença MIT.

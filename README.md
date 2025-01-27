# 📖 Web site Diário Pessoal com Django

Um projeto de diário digital desenvolvido com Django e Python, utilizando ORM para gerenciar o banco de dados. O projeto está atualmente em desenvolvimento.

## 🚀 Funcionalidades Planejadas
- Criação, leitura, atualização e exclusão (CRUD) de entradas no diário.
- Autenticação de usuários para garantir privacidade.
- Organização de entradas por data.
- Busca e filtros para facilitar a localização de entradas específicas.

## 🛠️ Tecnologias Utilizadas
- **Django**: Framework principal para o desenvolvimento web.
- **Python**: Linguagem de programação.
- **ORM (Object-Relational Mapping)**: Para interagir com o banco de dados de forma eficiente.
- **Banco de Dados**: SQLite

## ⚙️ Como Executar o Projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/caiohenriquefranca/diario-django
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd diario-online
   ```
3. Crie um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux
   .\venv\Scripts\activate  # Windows
   ```
4. Realize as migrações:
   ```bash
   python manage.py migrate
   ```
5. Inicie o servidor local:
   ```bash
   python manage.py runserver
   ```
6. Acesse o projeto no navegador:
   ```
   http://127.0.0.1:8000/
   ```
### Aplicação
<p align="center">
  <img class="rounded" src="./media/homepage.png" alt="Tela Inicial" width="800">
</p>

## 📝 Status do Projeto
🚧 **Em desenvolvimento**: Algumas funcionalidades ainda estão sendo implementadas e podem sofrer alterações.





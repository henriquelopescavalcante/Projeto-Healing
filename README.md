# 🏥 Projeto Healing

**Projeto Healing** é uma aplicação web desenvolvida com Django, 
voltada para o gerenciamento de clínicas médicas. O sistema permite o controle eficiente de pacientes,
médicos, agendamentos e histórico de consultas,
oferecendo uma solução robusta para clínicas de pequeno e médio porte.

## 🚀 Tecnologias Utilizadas

- Python 3.10+
- Django 4.x
- SQLite (ou outro banco de dados configurável)
- HTML5 + CSS3
- Bootstrap (opcional)

## ⚙️ Funcionalidades Principais

- Autenticação e autorização de usuários (Admin, Médicos, Recepcionistas)
- Cadastro e gerenciamento de pacientes
- Cadastro de médicos e especialidades
- Agendamento de consultas médicas
- Histórico de atendimentos por paciente
- Painel administrativo com controle completo dos dados
- Layout limpo e responsivo

## 📦 Instalação e Execução Local

Siga os passos abaixo para executar o projeto em sua máquina local:

```bash
# Clone o repositório
git clone https://github.com/henriquelopescavalcante/Projeto-Healing.git
cd Projeto-Healing

# Crie um ambiente virtual
python -m venv venv
source venv/bin/activate      # Para Linux/Mac
venv\Scripts\activate         # Para Windows

# Instale as dependências
pip install -r requirements.txt

# Execute as migrações
python manage.py migrate

# Crie um superusuário para acesso ao painel admin
python manage.py createsuperuser

# Inicie o servidor
python manage.py runserver


Depois, acesse o sistema no navegador:
http://127.0.0.1:8000

Para acessar o painel administrativo:
http://127.0.0.1:8000/admin

📁 Estrutura do Projeto


Projeto-Healing/
├── healing/              # App principal
├── templates/            # Templates HTML
├── static/               # Arquivos estáticos (CSS, JS)
├── db.sqlite3            # Banco de dados (padrão SQLite)
├── manage.py             # Script principal do Django
├── requirements.txt      # Dependências do projeto
└── README.md             # Documentação do projeto


🛠️ Melhorias Futuras
 Envio de lembretes por e-mail/WhatsApp

 Exportação de relatórios em PDF

 Dashboard com gráficos e estatísticas

 Integração com sistemas de convênio médico

🤝 Contribuindo
Contribuições são bem-vindas!
Sinta-se à vontade para abrir uma issue ou enviar um pull request.


👨‍💻 Autor
Desenvolvido por Henrique Lopes
https://github.com/henriquelopescavalcante | https://www.linkedin.com/in/henriquelopescs/

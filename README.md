Sistema de Cadastro de Usuários - Android
📱 Sobre o Projeto

Este projeto é um aplicativo Android desenvolvido em Java com o objetivo de realizar o cadastro e visualização de usuários.
O sistema permite:

Cadastrar novos usuários
Visualizar usuários cadastrados
Navegar entre os registros salvos
Cancelar operações e retornar ao menu principal

O aplicativo foi desenvolvido utilizando uma única Activity (MainActivity) responsável por controlar diferentes telas através de layouts XML.

🛠️ Tecnologias Utilizadas
Java
Android Studio
XML
Material Design Components
ConstraintLayout
📂 Estrutura do Projeto
app/
 ├── java/
 │    ├── MainActivity.java
 │    ├── Registro.java
 │    ├── TelaPrincipal.java
 │    ├── TelaCadastroUsuario.java
 │    └── TelaListagemUsuarios.java
 │
 └── res/
      └── layout/
           ├── tela_principal.xml
           ├── cadastro_de_usuarios.xml
           └── listagem_usuarios_cadastrados.xml
📋 Funcionalidades
🔹 Tela Principal

A tela principal funciona como menu inicial do sistema.

Opções disponíveis:
Cadastrar Novo Usuário
Listar Usuários Cadastrados
🔹 Tela de Cadastro

Responsável pelo cadastro de novos usuários.

Campos:
Nome
Telefone
Endereço
Ações:
Salvar cadastro
Cancelar operação
🔹 Tela de Listagem

Exibe os usuários cadastrados no sistema.

Recursos:
Navegação entre registros
Exibição do status atual
Retorno ao menu principal
🧠 Estrutura das Classes
📌 Registro.java

Classe responsável por armazenar os dados de cada usuário.

Atributos:
private String nome;
private String endereco;
private String telefone;
📌 MainActivity.java

Classe principal da aplicação.

Responsabilidades:
Inicializar a lista de registros
Controlar as telas
Exibir mensagens
Gerenciar a navegação
📌 TelaPrincipal.java

Controla o menu principal da aplicação.

Funções:
Abrir tela de cadastro
Abrir tela de listagem
📌 TelaCadastroUsuario.java

Responsável pelo cadastro dos usuários.

Funções:
Capturar dados digitados
Salvar registros
Confirmar ações com AlertDialog
📌 TelaListagemUsuarios.java

Responsável pela visualização dos registros.

Funções:
Exibir usuários cadastrados
Navegar entre registros
Atualizar status da listagem
🎨 Componentes Visuais Utilizados
Material Design

O projeto utiliza componentes modernos do Material Design:

MaterialButton
TextInputLayout
TextInputEditText
MaterialCardView
▶️ Como Executar o Projeto
1. Clonar o repositório
git clone https://github.com/WesleyLeandro0606/SistemaDeCadastro.git

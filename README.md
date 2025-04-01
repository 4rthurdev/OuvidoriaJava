# OuvidoriaJava

## 📌 Sobre o Projeto

**OuvidoriaJava** é uma aplicação de ouvidoria desenvolvida em Java que permite a gestão e registro de manifestações de usuários, como reclamações, sugestões, elogios e denúncias. A aplicação oferece uma interface simples e intuitiva para facilitar a comunicação e o tratamento dessas manifestações.

## 🚀 Tecnologias Utilizadas

- **Java** (versão 17 ou superior)
- **JavaFX** (Interface Gráfica)
- **MySQL** (Banco de Dados Relacional)
- **Maven** (Gerenciador de Dependências)

## 📂 Estrutura do Projeto

```
OuvidoriaJava/
│
├── src/                 # Código fonte da aplicação
├── resources/           # Arquivos de configuração e assets
├── README.md            # Documentação do projeto
├── pom.xml              # Arquivo de configuração do Maven
└── Main.java            # Classe principal para execução da aplicação
```

## 📦 Instalação

1. **Clone o repositório:**
```bash
$ git clone https://github.com/4rthurdev/OuvidoriaJava.git
$ cd OuvidoriaJava
```

2. **Importe o projeto em sua IDE preferida (Eclipse, IntelliJ, NetBeans) como um projeto Maven.**

3. **Configure o banco de dados MySQL:**
- Crie um banco de dados chamado `ouvidoria`.
- Configure as credenciais de acesso no arquivo de configuração do projeto.

4. **Compile e execute o projeto pela IDE ou via Maven:**
```bash
$ mvn clean install
$ mvn javafx:run
```

## 💻 Uso

1. **Inicie o aplicativo:**
- Execute a classe principal `Main.java` ou utilize o comando Maven `mvn javafx:run`.

2. **Acesse as funcionalidades da aplicação:**
- Registrar manifestações (reclamações, sugestões, elogios, denúncias).
- Consultar manifestações por tipo.
- Excluir manifestações.
- Visualizar relatórios resumidos.

## 📈 Funcionalidades

- Registrar manifestações (reclamações, sugestões, elogios, denúncias)
- Consultar manifestações por tipo
- Excluir manifestações
- Visualizar relatórios resumidos

## 📌 Próximos Passos

- Implementar autenticação de usuários
- Melhorar o design da interface gráfica
- Adicionar testes automatizados

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma `Issue` ou enviar um `Pull Request`.

---

Desenvolvido por [Arthur Vasconcelos](https://github.com/4rthurdev).

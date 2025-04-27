# Script-Web-Server

# Script de Configuração de Servidor Web

## Sobre o Projeto

Este script em **Bash** automatiza a configuração de um servidor web Apache, fazendo a instalação dos pacotes necessários e o deploy de uma aplicação estática hospedada no GitHub.

---

## Funcionalidades

- Atualização da lista de pacotes e upgrade do sistema.
- Instalação do servidor **Apache2**.
- Instalação do utilitário **unzip**.
- Download e extração de arquivos da aplicação.
- Cópia dos arquivos para o diretório padrão do Apache.

---

## Pré-requisitos

- Sistema baseado em **Linux (Debian/Ubuntu)**.
- Acesso como **root** ou usuário com permissões de **sudo**.
- **wget** instalado no sistema.

---

## Como Executar

1. Clone este repositório ou copie o script para o seu servidor.
2. Dê permissão de execução ao script:

    ```bash
    chmod +x nome-do-script.sh
    ```

3. Execute o script como superusuário:

    ```bash
    sudo ./nome-do-script.sh
    ```



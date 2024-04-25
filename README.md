## Baixando o código

1. **Clone o repositório Lina v3.10.7 para o diretório /opt/:**

    ```bash
    cd /opt/
    git clone https://github.com/joaofaria/lina-v3.10.7.git
    ```

## Instalando Node.js

2. **Baixe e instale o Node.js v16.14.0:**

    ```bash
    cd /opt
    wget https://nodejs.org/download/release/v16.14.0/node-v16.14.0-linux-x64.tar.xz
    tar -xf node-v16.14.0-linux-x64.tar.xz
    mv node-v16.14.0-linux-x64 /usr/local/node
    chown -R root:root /usr/local/node
    export PATH=/usr/local/node/bin:$PATH
    echo 'export PATH=/usr/local/node/bin:$PATH' >> ~/.bashrc
    ```

## Instalando dependências

3. **Instale o Yarn globalmente e as dependências do projeto:**

    ```bash
    cd /opt/lina-v3.10.9
    npm install -g yarn
    yarn install
    ```

## Iniciando o sistema

4. **Inicie o sistema em modo de desenvolvimento:**

    ```bash
    npm run dev
    ```

Essas instruções devem ajudá-lo a baixar o código, instalar as dependências necessárias e iniciar o sistema Lina v3.10.7 em modo de desenvolvimento. Certifique-se de seguir cada etapa cuidadosamente para garantir uma configuração correta.

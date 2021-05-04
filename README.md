<h1 align="center">
    Pokédex DOC
</h1>

### 📝 Sobre

Documentação da Pokédex API.

<br/>

### 🧰 Dependências

Este projeto foi desenvolvido utilizando das seguintes dependências:

- [insomnia-documenter](https://www.npmjs.com/package/insomnia-documenter)
- [serve](https://www.npmjs.com/package/serve)

<br/>

### 💻 Como utilizar ?

Siga os passos a seguir para inicializar a documentação

<br/>

#### **Clonando**

  * Clone o repositório para sua máquina local com o comando:

    ```shell
    git clone https://github.com/augustobritodev/pokedex-doc.git
    ```

<br/>

#### **Inicializando**

 * Instalar a dependência ***serve***:

    ```shell
    npm install -g insomnia-documenter
    ```

* Inicie o servidor com:

    ```shell
    cd pokedex-doc
    npx serve
    ```

  >   Acessar via [http://localhost:5000](http://localhost:3333)

<br/>

#### **Atualizando o Projeto**
  * O arquivo .JSON que alimenta a documentação pode ser exportado do Insomnia, dessa forma toda alteração que for feita no insomnia deve-se gerar uma nova documentação usando os seguintes comandos.

    ```shell
      cd pokedex-doc
      npx insomnia-documenter --config nome-do-arquivo.json     
    ```
  


  




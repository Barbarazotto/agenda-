# Agenda em Python usando Flask/

Este protejo foi eleaborado para permitir o aprendizado de conceitos como padrão de projeto MVC (Model-View-Controller), framework Flask e seus componentes, variáveis de ambiente, paradigma de programação orientado a objetos e reforço de fundamentos da linguagem de programação Python.

Para implementar este prjeto localmente, siga os seguintes passos: 

1. Faça um frok deste repositório, clicando no botão `Flork`

2. Clone este repositório localmente: 

    ~~~bash
    git clone <url_seu_repositorio>
    ~~~

3. Abra o projeto utilizando sue IDE preferido.

4. Crie, preferencialmente, um ambiente virtual utilizando uma versão do Python 3.12.10:

    ~~~bash 
    python -m venv .venv 
    ~~~

5. Ative seu ambiente virtual.

    No Bash:

    ~~~bash 
    source .venv/Scripts/activate 
    ~~~

    No PowerShell:
   
    ~~~powershell
    .\.venv.\Scripts\Activate.ps1
    ~~~ 

6. Instale todas as dependências constantes no arquivo `requirements.txt`:

    ~~~python 
    pip install -r requirements.txt
    ~~~

7. Copie o arquivo `.env.exemple`, colo na raiz do projeto e renomeie esse arquivo para `.env`.

8. Edite o arquivo `.env` para definir o caminho do seu banco de dados na 
constante `DATABASE`. Exemplo:

    ~~~env
    DATABASE='./data/meubanco.db'
    ~~~

9. Rede a aplicação no Python utilizando o comando:

    ~~~bash 
    flask run
    ~~~ 

10. Acesse a aplicação no endereço e porta indicados no terminal. Exemplos: 
`https://127.0.0.1:500`
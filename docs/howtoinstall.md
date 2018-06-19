## Instalação

### Virtualenv

##### **1. Instale o Pip**
Para visualizar se você possui o pip instalado, use:
```shell
pip --version
```

Caso não tenha o pip instalado, use:
```shell
sudo apt-get install python3-pip
```


##### **2. Instale o Virtualenv**
Para visualizar se você possui o virtualenv instalado, use:
```shell
virtualenv --version
```

Caso não tenha o pip instalado, use:   
```shell
sudo pip3 install virtualenv
```


##### **3. Crie um Virtualenv com Python3**
```shell
virtualenv -p python3 env
```


##### **4. Entre no Virtualenv**
Entre na pasta que contém seu virtualenv e use:  

```shell
source env/bin/activate
```

---

Após criar um _virtualenv_, navegue até o diretório `trace_feature` e execute o seguinte comando:   

```shell
$ pip install .
```

### Execução do projeto:
Para executar o projeto, use o comando:

```shell
trace-feature -f [feature] -s [linha do cenário]
```

Os argumentos são opcionais e não precisam ser especificados depois do comando. Vale lembrar também que para que o comando seja executado sem parâmetros, é necessário navegar até a pasta do projeto onde se deseja executar a ferramenta.

Para obter ajuda sobre o comando e os argumentos, basta usar

```shell
trace-feature --help
```

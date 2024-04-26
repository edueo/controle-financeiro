# Controle Financeiro

Mais um sistema de finanças pessoais


## Setup ambiente 

1. Instalar autoenv **Siga as orientações: https://github.com/hyperupcall/autoenv**

```
# with cURL
curl -#fLo- 'https://raw.githubusercontent.com/hyperupcall/autoenv/master/scripts/install.sh' | sh
```

2. Crie o ambiente virtual

```
python -m venv .venv

```

```
cp .env.example .env

```
Obs: Caso seu virtualenv tenha outro nome, altere para o nome correto no arquivo .env



## Ferramentas

- ASDF
- [autoenv](https://jay.gooby.org/2023/06/13/asdf-python-and-automatically-enabling-virtual-envshttps://jay.gooby.org/2023/06/13/asdf-python-and-automatically-enabling-virtual-envs)


## teste mermaid

```mermaid
graph LR 
    A{Do you know how to write great PHP code?} --> B[No]
    A --> C[Yes] 
    C --> E(Awesome!) 
    B --> D{Did you read Clean Code in PHP?} --> F[No] 
    D --> G[Yes] 
    G --> H(Please read it again) 
    F --> I(Please read it)
```

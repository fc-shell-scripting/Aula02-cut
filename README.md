# CUT

O comando cut faz a separação de dados. Este comando pode ser usado diretamente ou como parte de algum script.
Como este comando é muito útil, vamos ter uma seção apenas para ele.

## Forma de uso
O comando abaixo faz a separação do arquivo texto usando o delimitador vírgula (**,**), e mostra apenas o segundo campo
``` bash
cut -d',' -f2 arquivo
```

Para exemplos mais simples, podemos usar o comando pipe para alterar a entrada de dados:
``` bash
cat arquivo | cut -d' ' -f4
```

> Vale ressaltar que o parâmetro **-d** permite apenas um caracter para realizar o corte. Leve isso em conta quando for desenvolver seus scripts.

## Exercícios
1. Utilize o comando cut no arquivo cadastro.csv para mostrar na tela apenas o nome e endereço dos usuários
2. Mostre o nome dos usuários do arquivo cadastro.csv para mostrar os nomes na ordem inversas do que está no arquivo.
3. carregue o nome e documento dos usuários que possuem telefone no Brasil (iniciam com +55)

## Desafio
Mostre na tela o endereço ip de cada placa de rede disponível na máquina onde o linux está

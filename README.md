# SisOp
Repositório para ex. da disciplina de Sistemas Operacionais

Ex 01. 

```
echo "Mauricio K. Ferret"
```
Ex 02.

```
echo "Mauricio K. Ferret" > cliente_01.txt
```
Ex 03.

```
echo "Frederico Westphalen" >  cliente_01.txt
```
Ex 04.

```
mkdir clientes
ls
```
Ex 05.

```
mv cliente_01.txt clientes
```
Ex 06.

```
cp cliente_01.txt cliente_01.txt_bkp
```
Ex 07.

```
rm cliente_01.txt
```
Ex 08. e Ex 09.
```
vi clientes.sh *obs:. Criado com .sh para tornar arquivo executável, .script estava dando erro.
echo "Mauricio K. Ferret"
echo "Mauricio K. Ferret" > cliente_01.txt
echo "Frederico Westphalen" >  cliente_01.txt
mkdir clientes
mv cliente_01.txt clientes
cd clientes
cp cliente_01.txt cliente_01.txt_bkp
rm cliente_01.txt
:wq
chmod -x cliente.sh
sh cliente.sh
````
Ex. 10

```
comando cal
 
Apresenta calendário do mês corrente com a data de hoje sombreada 

echo|cal > hoje.txt * Comando desmarcou no calendário o dia de hoje, retirabdndo o sombreado. O Comando pipe serve para combinar comandos e filtrar a saída. Neste caso  o comando echo foi combinado com o comando  > que é para limpar (excluir),gerando um novo arquivo hoje.txt 
```

Ex 11. e Ex 12.

Efetuado download do arquivo cidades_sc.txt conforme pedia no exercício;
``` 
comando grep Balneario cidades sc.txt
apresentou o resultado da busca por cidades que possuem Balneario no nome:
Balneario Arroio do Silva
Balneario Barra do Sul
Balneario Camboriu
Balneario Gaivota
```
Ex. 13.

ao executar o comando grep balneario cidades_sc.txt não retornou nenhuma cidade pois o "b" é minúsculo e o programa é case sensitive.

Ex. 14.

Ao executar o comando grep "do sul" cidades_sc.txt não retornou nenhuma cidade pois não deve-se usar aspas para esta procura.

Ao executar grep do sul cidades_sc.txt o programa retorna todas as cidades que possuem "do" e/ou "sul" no nome

Ex: Abelardo Luz
    Balneario Barra do Sul
    Ponte Alta do Norte
   
Ex 15.

utilizando o comando cat cidades_sc.txt | grep Balneario

Retornou as cidades:
Balneario Arroio do Silva
Balneario Barra do Sul
Balneario Camboriu
Balneario Gaivota

Ex 16.

```
vi balneario.txt
i > Balneario Barra do Sul
    Balneario Camboriu
    Balneario Gaivota
:wq
```
Ex 17. 

```
utilizado gzip balneario.txt pois o comando tar estava dando erro. 

criado arquivo balneario.txt.gz e renomeado para balneario.txt.gz

```

Ex 18.

```
Descompactado o arquivo com gzip -d compactado.gz
extraido o conteudo para arquivo 'compactado'
renomeado para compactado.txt
```


~





    










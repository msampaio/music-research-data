# Harpa

Este repositório contém os dados sobre pedais da harpa usados no artigo publicado na Revista [ICTUS](https://periodicos.ufba.br/index.php/ictus/index).

## Estrutura dos dados

A estrutura dos dados consiste em um documento em formato `csv` contendo 2187 entradas referentes às configurações ou armações dos pedais da harpa. Para cada configuração estão disponíveis as seguintes informações:

- Índice em formato ternário (ver artigo)
- Notas em disposição escalar
- Notas em disposição radial
- Conjunto de notas
- Forma prima do conjunto de notas
- Número da classe na tabela de Forte
- Acidentes
- Vetor classe-intervalar (1,2,3,4,5,6)

## Exemplo dos dados

- [harpa.csv](harpa.csv)

```csv
Index,Notes (scalar),Notes (radial),PC Set,Prime Form,Forte class,Accidents,1,2,3,4,5,6
0,Cb Db Eb Fb Gb Ab Bb,Db Cb Bb Eb Fb Gb Ab,B13468A,013568A,7-35,"(0, 0, 0, 0, 0, 0, 0)",2,5,4,3,6,1
1,Cb Db Eb Fb Gb Ab Bn,Db Cb Bn Eb Fb Gb Ab,B13468B,024579,6-32,"(0, 0, 0, 0, 0, 0, 1)",1,4,3,2,5,0
2,Cb Db Eb Fb Gb Ab B#,Db Cb B# Eb Fb Gb Ab,B134680,0124579,7-27,"(0, 0, 0, 0, 0, 0, 2)",3,4,4,4,5,1
10,Cb Db Eb Fb Gb An Bb,Db Cb Bb Eb Fb Gb An,B13469A,0124679,7-29,"(0, 0, 0, 0, 0, 1, 0)",3,4,4,3,5,2
```
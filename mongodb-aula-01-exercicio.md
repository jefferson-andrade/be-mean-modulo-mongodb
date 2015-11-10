# MongoDB - Aula 01 - Exercício
autor: Jefferson Andrade Agostinho

## Importando os restaurantes

jefferson@Inspiron-5547:~/workspace/classes/dagora/mongodb/class1$ mongoimport --db be-mean --collection restaurants --drop --file restaurants.json

2015-11-10T00:49:22.473-0200	connected to: localhost

2015-11-10T00:49:22.473-0200	dropping: be-mean.restaurants

2015-11-10T00:49:23.530-0200	imported 25359 documents

jefferson@Inspiron-5547:~/workspace/classes/dagora/mongodb/class1$

## Contando os restaurantes

Inspiron-5547(mongod-3.0.7) test> use be-mean

switched to db be-mean

Inspiron-5547(mongod-3.0.7) be-mean> db.restaurants.find({}).count()

25359

# Modelo Relacional
Foi um modelo proposto por Edgar F. Codd em 1970 e garante uma grande independência de dados.
## Introdução
Modelo baseado na Teoria dos Conjuntos. Podemos pensar em Sets da Java Collectons 
> Java Colections por exemplo um set não podia ter elemenos repetidos e a ordem não interesava.


Este modelo é baseado na notação matemática de "Relação" e é representado por tabelas. Dispõe de um sistema formal de manipulação das relações através de **álgebra relacional**
Começou a ser comercializado nos anos 80. Teve um boom nos anos 90.
## Conceitos
- Atributo (A1,A2,...,An)
Representam o tipo de dados a armazenar, 
(Resto dos slides)
## Relação
|Atributes  |  |
|--|--|
|tuples  |  |
### Chaves
- Superchave(*superkey*) - Conjunto de atributos que identificam de forma única os tuplos de relação
- Chave Candidata (candidate key) - Subconjunto de atributos de uma superchave que não pode ser reduzido sem perder essa qualidade de superchave
- (...)

#### Superchave e chaves candidatas
Cada rekação tem pelo menos uma superchave (conjuto de todos os atributos)
**Exemplo**
**Estudante(Nome,Email,NMec,Curso)**
Superchaves:
{Nome,Email,NMec,Curso}
{Nome,Email,NMec}
{Nome,Email}

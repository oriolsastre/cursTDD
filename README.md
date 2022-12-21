# cursTDD
Curs de TDD (Test Driven Developement) a l'IT Academy.


Primer escrivim el test. Què vull que faci aquella funcio. HA DE FALLAR
Escrivim la classe/metode i ho deixem en blanc.
Falla el test.
Escric codi de nou que satisfaci el test. Codi net/pragmàtic/simple/estúpid 
Un cop els test estan satisfts, tunegem el odi amb bones pràctique si tal.
Tornem a passar el test amb els nous cnanvis, que en principi no hem fet res, però ens equiovquem i cal comprovar-ho.
Si fem canvis petits, cal buscar sempre el test



test fail -> test passed -> refactoritzar -> inici


model vista controlador (MVC)

el control rep i envia on toca, a una capa de servei (aquesta fa servir una lògica de negoci; no són els models)
El controller no crida MAI a la DB, retorna la respota. El contingut de la petició el delega. El controlador també tracta errors.
Els MW servien business logic.
A la DB li demanem coses amb uns business objects <- això són els Models en node
els busines object MAI han de fer lògica de negoci. Només tenen dades retornades per la DB
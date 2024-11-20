# Cloud Solution Video Store
Arquitetura para um sistema em nuvem para a locadora e vídeos

Precisamos propor uma arquitetura para um sistema em nuvem para a locadora e vídeos descrita abaixo. Uma pequena locadora de vídeos possui aproximadamente 2000 fitas de vídeo e mais de 10000 DVD’s além de 5000 CDS de artistas musicais variados, cujo empréstimo deve ser controlado.

a) Cada fita, DVD ou CD possui um número. Para cada filme, é necessário saber seu título e sua categoria (comédia, drama, aventura,). Cada filme recebe um identificador próprio. Para cada fita, DVD ou CD é controlado que filme ela contém. Para cada filme ou álbum há pelo menos uma fita, DVD ou CD, e cada fita, DVD ou CD contém somente um filme associado. Alguns poucos itens de locação necessitam de duas fitas, DVD ou CD’s.

b) Os clientes podem desejar encontrar os filmes, álbuns ou shows estrelados pelos seus atores, artista ou participações especiais e locais prediletos. Por isso, é necessário manter a estas informações referenciadas em cada volume. Nem todo filme possui estrelas. Para cada ator ou artista os clientes às vezes desejam saber o nome real, como a data de nascimento.

c) A locadora possui muitos clientes cadastrados. Somente clientes cadastrados podem alugar fitas. Para cada cliente é necessário saber seu prenome e seu sobrenome, seu telefone e seu endereço. Além disso, cada cliente recebe um número de associado.

d) Precisamos, além disto, tudo saber no acervo quais fitas, DVDs ou CDs estão no estabelecimento e quais estão emprestados.

e) Finalmente, desejamos saber que fita, DVD ou CD cada cliente tem emprestadas. Um cliente pode ter várias fitas, DVD ou CD em um instante do tempo. Devem ser mantidos registros históricos de aluguéis.

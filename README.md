# Infnet - PB - Desenvolvimento Front-End
Projeto de Bloco da matéria de Desenvolvimento Front-End.

## Apresentação
Trata-se de um sistema para auxiliar pessoas que se conheceram por aplicativos de namoro a marcarem seu encontro, o sistema irá sugerir localizações recomendadas da cidade para o encontro, tais como restaurantes, pontos turísticos e parques. O sistema irá fornecer ajuda a pessoas que estejam em perigo ou que caíram em algum tipo de golpe.

### Cenários


* __Cenário 1:__

__Cena representada:__
Marcação de rotas turísticas ideais para encontros.

__Atores envolvidos:__ 
João (Usuário)

__Ação:__ 
Após conhecer e conversar com Maria por um aplicativo de namoro, João, morador de Ponta Grossa - PR, marcou o seu 1° encontro com Maria na cidade onde ela mora (Curitiba - PR).
Querendo surpreendê-la, João decidiu que a melhor forma de conquistar Maria seria levando ela para passear nos belos parques e pontos turísticos da cidade ou levá-la para jantar em um restaurante.
Com isso em mente, João encontrou o Sistema de auxílio para encontros, um site que mostra ao usuário sugestões de lugares românticos e restaurantes para futuros casais.
Para começar o planejamento do seu encontro João tem que se cadastrar no site e fazer login. Somente após o login João terá acesso as avaliações feitas pelos outros usuários sobre os locais da cidade.

__User Stories:__

__User Story 1:__
Como usuário, gostaria de ranquear os pontos turísticos melhor avaliados de Curitiba-PR, para obter como resultado um encontro bem sucedido.


__User Story 2:__
Como usuário, gostaria que o sistema me forneça mais de uma rota até o local desejado, pois como não conheço a cidade pode ser que a rota mais rápida não seja a melhor.


* __Cenário 2:__

__Cena representada:__
Rota de fuga em caso de encontro ruim.

__Atores envolvidos:__ 
Michele (Usuária).

__Ação:__ 
Após conhecer e conversar com "Felipe" por um aplicativo de namoro, Michele decidiu jantar em um Restaurante de luxo da cidade, o qual foi sugerido por Felipe pois ele pagaria toda a conta do encontro.
Porém, no local de encontro Michele se surpreendeu porque Felipe não era a mesma pessoa das fotos do aplicativo de namoro. Michele questionou Felipe sobre este fato mas foi convencida por ele de suas boas intenções por conta da boa lábia de Felipe. Ainda mais por ser um rapaz bem-apessoado.
Ao final do jantar Michele foi surpreendida outra vez, porque Felipe falou que havia esquecido a carteira em casa, mas Michele não poderia pagar a conta daquele restaurante caro e porque Felipe havia prometido pagar.
Portanto Michele se recusou a pagar e Felipe se transformou em outra pessoa, totalmente diferente da pessoa simpática que havia mostrado ser, anteriormente. Aí Michele percebeu que provavelmente se tratava de um golpista e que o nome dele provavelmente não deveria ser Felipe também.
Então Michele resolveu sair do encontro direto para uma delegacia próxima para denunciar o rapaz, porém Michele não sabia a localização de nenhuma delegacia.
Então ela acessou o sistema e buscou a delegacia mais próxima bem como a rota mais rápida para diversos meios de transporte disponíveis sugeridos pelo sistema.

__User Stories:__

__User Story 1:__

Como usuária, gostaria de localizar as delegacias mais próximas para que meu caso possa ser atendido e investigado.


__User Story 2:__
Como usuária, eu gostaria que o site forneça algumas informações e dicas de como proceder em caso de encontro ruim e identificar previamente má intenções por parte da pessoa que estou encontrando, bem como leis que versam sobre temas como falsidade ideológica e temas relacionados.
<p></p>

### Especificação dos Requisitos do Sistema de auxílio para encontros

* Requisitos Funcionais

| ID | Descrição | Prioridade |
|----|-----------|------------|
| RF-001 |	O sistema deverá ter uma tela com informações e dicas para encontros.	| Essencial |
| RF-002 |	O sistema deverá possuir um método para cadastrar o usuário.	| Essencial |
| RF-003 |	O sistema deverá ter uma caixa de pesquisa.	| Essencial |
| RF-004 |	O sistema deverá possuir um sistema de localização.	| Essencial |
| RF-005 |	O usuário poderá ser capaz de visualizar o seu histórico de pesquisas realizadas.	| Essencial |
| RF-006 |	O usuário poderá ser capaz de classificar os locais que visitou.	| Essencial |
| RF-007 |	O usuário poderá visualizar rotas entre locais selecionados.	| Essencial |
| RF-008 |  O usuário poderá ser capaz de realizar comentários sobre os locais visitados.	| Essencial |

* Requisitos Não funcionais

| ID | Descrição | Prioridade |
|----|-----------|------------| 
| NF-001 |	O sistema deverá ter uma interface responsiva.	| Usabilidade |
| NF-002 |  O sistema deverá possuir uma função de rolagem automática para determinado elemento selecionado pelo usuário.	| Usabilidade |
| NF-003 |  O sistema deverá se utilizar da API do Google Maps.	| Usabilidade |
| NF-004 |  O sistema não deverá apresentar problemas de lentidão.	| Performance |
| NF-005 |	O usuário poderá salvar seus dados de autenticação para próximos acessos.	| Performance |
| NF-006 |  O sistema deverá respeitar as boas práticas de design e possuir uma interface gráfica intuitiva.	| Usabilidade |
| NF-007 |  O sistema deverá apresentar uma tela para usuários não logados e usuários logados.	| Segurança |
| NF-008 |  O sistema deverá possuir modo de autenticação por meio do Google e Facebook. | Segurança |
| NF-008 |  O sistema deverá ter boas práticas com base na Lei Geral de Proteção a Dados.	| Segurança |

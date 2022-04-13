# Modelagem de requisitos
Os casos de uso são uma técnica de descoberta de requisitos, sendo que em sua forma mais simples, um caso de uso identifica os atores envolvidos em uma interação e dá nome ao tipo de interação. Essa é, então, suplementada por informações adicionais que descrevem a interação com o sistema. A informação adicional pode ser uma descrição textual, que foi o método completar que o grupo escolheu, mas pode ser feito através de um ou mais modelos gráficos, como diagrama de sequência ou de estados da UML.

O conjunto de casos de uso representa todas as possíveis interações que serão descritas nos requisitos de sistema. Um diagrama de caso de uso possui os seguintes elementos:

- Atores: que podem ser pessoas ou outros sistemas, e são representados como figuras ‘palito’;
- Classe de interação: representa as ações dos usuários ou do sistema, e são representadas por uma elipse;
- Relacionamentos: fazem a ligação entre os atores e a interação;
- Caixa de limite do sistema: define um escopo do sistema para os casos de uso. Todos os casos de uso fora da caixa são considerados fora do escopo do sistema.

## Caso de uso geral

<center>

<div style="width: 960px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:960px; height:480px" src="https://lucid.app/documents/embeddedchart/3c39240a-5c82-4739-a93a-5839c6e8c5d4" id="lNK-hjTptCpO"></iframe></div>

</center>

## Descrição dos casos de uso

### Caso 1: Salvar notas
<center>

| Caso 1 | Detalhamento |
| :--: | :----------: | 
| Descrição |Ao acessar a tela inicial do aplicativo, o ator conseguir visualizar o menu para manuseio de sua nota. | 
| Ator(res) | Usuário| 
| Pré-condições | O ator deve ter como acessar o aplicativo. O ator deve ter pelo menos uma nota para começar o manuseio. | 
| Fluxo | 1. O ator precisa abrir o aplicativo 2. O ator precisa entrar no menu de manuseio. 3.  O ator precisa escolher o que fazer com a nota. | 
| Pós-condições | O ator poderá ter visualizado todas as informações relacionadas ao nome |
| Rastreabilidade |RF01 RF02 RF03 RF04 | 

</center>

<figcaption style="text-align: center">Tabela 1 - Caso 1 - Salvar notas</figcaption>

### Caso 2: Status Notas
<center>

| Caso 2 | Detalhamento |
| :--: | :----------: | 
| Descrição |Ao acessar a tela inicial do aplicativo, o ator conseguir visualizar o menu para status de sua nota. | 
| Ator(res) | Usuário| 
| Pré-condições | O ator deve ter como acessar o aplicativo. O ator deve ter pelo menos uma nota para começar o manuseio. | 
| Fluxo | 1 - O ator precisa abrir o aplicativo 2. O ator precisa entrar em status. | 
| Pós-condições |O ator terá visto status de sua nota.| 
| Rastreabilidade |RF05 RF06 | 

</center>

<figcaption style="text-align: center">Tabela 2 - Caso 2 - Status Notas</figcaption>

### Caso 3: Sobre Nós
<center>

| Caso 3 | Detalhamento |
| :--: | :----------: | 
| Descrição |Ao acessar a tela inicial do aplicativo, o ator conseguir visualizar sobre o sistema. | 
| Ator(res) | Usuário| 
| Pré-condições | O ator deve ter como acessar o aplicativo. | 
| Fluxo | 1. O ator precisa abrir o aplicativo 2. O ator precisa entrar em Sobre Nós. | 
| Pós-condições | Ator poderá ter acesso ao projeto sobre o desenvolvimento do Sistema.|
| Rastreabilidade |RF07 | 

</center>

<figcaption style="text-align: center">Tabela 3 - Caso 3 - Sobre Nós</figcaption>

## Referências e Bibliografias
> SOMMERVILLE, Ian. Engenharia de Software. 9.ed. São Paulo: Pearson Prentice Hall, 2011. 529 p.
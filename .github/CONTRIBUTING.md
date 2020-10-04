# Políticas de contribuição

## 1. Política de Issues
Caso encontre um bug ou tenha alguma sugestão de melhoria para o software é possível criar uma issue seguindo os passos abaixo:

1. Escolha o tipo de issue a ser criado (funcionalidade, documentação ou correção de bug)
2. Escreva um título sucinto para a issue
3. Preencha a descrição da issue seguindo os passos e as orientações do template que será mostrado
4. Preencha informações adicionais caso possua (executores, épico, marco, etc)

Tanto o título como a descrição da issue devem estar escritos em inglês e seguir suas regras de sintaxe e semântica. 

## 2. Política de Branches

## 2.1 Gitflow
O Git Flow do repositório de documentação será tratado da forma mostrada nessa [imagem](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/images/gcs/GitFlowDocumentation.png). Para uma mudança chegar a branch master (branch estável) os passos abaixo são seguidos:

1. Toda nova branch deve ser feita a partir da master
2. Ao resolver a issue proposta a nova branch deve ser merjada e comparada em relação a master
3. Caso o PR seja aprovado pela equipe a nova branch será deletada e seu conteúdo integrado a master

## 2.2 Regras de Nomenclatura
Toda nova branch criada nos repositórios Stay Safe deve se propor a resolver uma issue específica, o nome da branch deve seguir as seguintes regras:

1. Conter o código da issue fornecido pelo GitHub
2. Ser curto e expressivo a respeito da issue a ser tratada
3. As palavras devem ser separadas por underscore "-"
4. Ser escrito em "lower case"

Exemplo:

    2-vision-document

## 3. Política de Commits
Os commits devem ser atômicos (uma contribuição pequena para resolver um problema específico). A mensagem do commit deve relatar o que foi feito de maneira sucinta e direta, além disso ela precisa estar em inglês, começar com um verbo e com a primeira letra maiúscula. 

Contribuições feitas por mais de uma pessoa devem conter o comando "Co-authored-by" para identificar todos os autores envolvidos.

Exemplo de contribuição feita por um autor:

    git commit -m "Add database diagram image."

Exemplo de contribuição feita por mais de um autor:

    git commit -m "Create user model.

    Co-authored-by: Pessoa <emailgit@email.com>"


## 4. Política de Pull Request
Para realizar um Pull Request (PR) para o repositório é necessário seguir os passos abaixo.

1. Ao resolver uma issue suba suas contribuições e crie um Pull Request
2. Escreva um título sucinto para o PR 
3. Preencha a descrição do PR seguindo os passos e as orientações do template que será mostrado
4. Ligue o PR com a issue que ele resolve
5. Preencha informações adicionais caso possua (executores, revisores, etc)

### 4.1 Política de Aprovação

Para um Pull Request ser aprovado no repositório de documentação a contribuição feita deve:

1. Ser relevante para o projeto
2. Resolver apenas a issue específica ao qual se habilita a tratar
3. Respeitar todos os critérios de aceitação definidos na issue
4. Estar na língua portuguesa e seguir as normas desta 
5. Estar na pasta e formato adequados
6. Ser aprovada na integração contínua e nas ferramentas que ela executa

## 5. Política de Documentação
Para contribuir com a documentação do projeto as regras definidas de commit, issue e PR também se aplicam, além destas pedimos atenção aos pontos abaixo:

1. Um novo documento deve ser criado dentro da pasta produto ou projeto dependendo do que ele trata
2. Para adicionar imagens a um documento deve-se fazer o upload delas em uma nova sub-pasta dentro da pasta images. Exemplo: "images/NomeDoNovoDocumento/persona.jpeg"
3. Todo documento deve conter um tópico de Introdução para dizer do que ele se trata

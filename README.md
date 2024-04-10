# Bem-vindo ao Projeto 👋

Este projeto foi desenvolvido durante o estágio para a agência experimental da universidade. O objetivo era criar um site para o curso de Ciência da Computação, utilizando a framework Hugo.

## Sobre o Projeto :octocat: 

O site desenvolvido visa proporcionar informações relevantes sobre o curso, como eventos, projetos, corpo docente e muito mais. Utilizamos a framework Hugo para garantir eficiência e facilidade na manutenção.


Itens que foram necessários para o desenvolvimento do projeto:

- [ O template ](https://github.com/HugoBlox/theme-research-group) 🌐
- [Configurações do ambiente de desenvolvimento](https://www.youtube.com/watch?v=hjD9jTi_DQ4)💎
- [Documentação do Hugo](https://gohugo.io/documentation/) 📚
- [Entendimento de como o Hugo funciona e exemplos de código](https://kinsta.com/pt/blog/site-estatico-hugo/)📖
- [Vídeo que ajuda a entender como criar pelo terminal](https://www.youtube.com/watch?v=RBhCQMbKFSo&t=5345s&pp=ygUOSFVHTyBGUkFNRVdPUks%3D)
- [Ícones para embelezar](https://gist.github.com/rxaviers/7360908)💄

## Como Começar

1. Clone o repositório: `git clone https://github.com/seu-usuario/seu-repositorio.git`
2. Instale as dependências: `npm install`
3. Execute o projeto localmente: `npm start`

Fique à vontade para explorar o código-fonte e abrir [issues](link_para_nova_issue) para relatar problemas🐛  ou sugerir melhorias.🌱

Pode dar uma olhada nesses slides que possuem links que podem ajudar : [apresentação do site}(https://www.canva.com/design/DAF7CgzrHO8/p2RZZEAVAD-iSVUpe5IoVQ/view?utm_content=DAF7CgzrHO8&utm_campaign=designshare&utm_medium=link&utm_source=editor)


# Estrutura do Projeto

Aqui está uma breve descrição de algumas das pastas importantes neste projeto:


# na pasta 📂 assets

Temos duas pastas, uma chamada de `scss` e outra chamada de `media`, além de um arquivo chamado `jsconfig.json`.



No folder 📂 `media`, temos diversas imagens e um folder chamado `icons` que contém um arquivo chamado `.gitkeep`. As imagens são predominantemente do tipo jpg, exceto `icon.png`, que é o ícone que aparece como emblema.


---

No folder 📂 `config/_default`temos os seguintes itens :

- **`config.toml` (ou `config.yaml` ou `config.json`)**: Contém configurações globais para o site. Aqui, você mencionou a variável `title` que define o título do site da universidade. Além disso, pode conter configurações para outras funcionalidades básicas, como a linguagem do site.

- **`languages.yaml`**: Utilizado para determinar as configurações de idiomas do site. Pode conter informações sobre traduções e configurações específicas de cada idioma.

- **`menus.yaml`**: Define menus, como o menu principal (`main`). Aqui, você configura as páginas que deseja incluir no menu e os nomes visíveis para os usuários (`name`).

- **`module.yaml`**: Utilizado para configurações relacionadas a módulos do Hugo. Módulos são uma maneira de compartilhar e reutilizar partes do seu site em diferentes projetos.

- **`params.yaml`**: Contém parâmetros adicionais que podem ser usados em várias partes do seu site. Parece ser utilizado para configurar parâmetros gerais.

---

##📂folder content
Dentro da pasta `content`, as seguintes subpastas compõem a estrutura do site:

#📂  folder authors

No corpo docente, temos os professores e a coordenação. Cada folder ou pasta 📂  tem o nome do professor(a), e dentro dessa pasta, haverá um arquivo chamado `_index.md` com as informações dos professores, seguindo o mesmo modelo. Além disso, cada pasta contém uma imagem chamada `avatar.png` com cor de fundo padrão para todos. Este folder serve para os alunos conhecerem melhor os professores.

# 📂  folder contact

Existe um único arquivo chamado `index.md` que basicamente contém o telefone da Católica e a localização da Unicap.

# 📂  folder event

Segue o mesmo padrão de um folder para cada postagem. É recomendado utilizar um nome fácil de compreensão que defina bem o conteúdo da postagem do evento. Por exemplo, o folder "iee" possui dois itens: uma imagem coletada no Instagram e um arquivo chamado `index.md` que descreve o evento e ajuda a incentivar a maior participação dos alunos.

# 📂 folder  extra

Podemos ter inúmeros folders 📂 falando sobre os projetos de extensão que já foram concluídos e também os que estão acontecendo. Por enquanto, só possui um outro folder que segue a estrutura de escrita `data - titulo`. Esta postagem é sobre o projeto de extensão "Technovation For Girls" que aconteceu no ano de 2023. Comparando com as outras postagens e modelos, notamos que é possível adicionar mais de uma imagem à postagem. Ele também possui um arquivo chamado `_index.md` que determina a forma da paginação.

# 📂  folder people

Existe apenas um arquivo chamado `index.md`. Nesse arquivo, podemos mudar um título que aparece acima da paginação de "authors", onde temos o nosso corpo docente. Além disso, podemos criar categorias de grupos de usuários, como professores, pesquisadores, coordenação.

# 📂  folder  post

Possui diversos folders que seguem a estrutura semelhante entre si e a forma que deve ser nomeado. Parecido no aspecto de ter uma descrição ou vários comentários e curiosidades no arquivo chamado `index.md` e uma imagem que deve/precisa ser nomeada como `featured.png`. Além disso, há um arquivo chamado `_index.md` que serve para determinar a forma que é feita a paginação.

# 📂 folder  projects

Temos os projetos de iniciação científica que seguem uma estrutura de nomenclatura semelhante aos outros como `data - titulo`. No entanto, esses folders não possuem uma imagem como item e só contêm um arquivo chamado `index.md`, onde temos o título, a data, os professores que participam do projeto, informações importantes como se o projeto ainda está em andamento, palavras-chave e, claro, a descrição do projeto. Ainda dentro do folder `projects`, temos um arquivo chamado `_index.md` que mantém o formato da página.

# 📂  folder publication

Segue a seguinte estrutura: tipo de publicação ou local de publicação, professor, tema. Exemplo: o folder `conference-madeiro-dislexia` que possui dois itens: um chamado de `cite.bib` e outro é o arquivo chamado `index.md`. Este contém informações importantes com os autores, o título, a data de publicação, o tipo de publicação, o abstract, as tags e onde pode ser visto, o link de visualização.

# 📂 folder tour

É um folder importante por ser a primeira página que é visualizada pelo usuário. Nela, podemos mudar/escolher o nome do filename, que nada mais é que o nome do arquivo que está guardado do folder `icon` que está dentro do folder `media`. Além disso, podemos escolher um título, escrever uma frase que fica no topo da paginação.                     ---
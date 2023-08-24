</br>Tabela USUARIO{
    </br>-IDusuario
    </br>-Nome
    </br>-Função
    </br>-Contato
    </br>-Status
</br>}
</br></br></br>Tabela Extensão{
    </br>-IDextensão
    </br>-Responsavel
    </br>-Local
    </br>-Contato
    </br>-Descrição
</br>}
</br></br></br>Tabela LIVROS {
</br>-ID do Livro: Um identificador único para cada livro na tabela.
</br>-Título: O título do livro.
</br>-Autor(es): Os autores do livro. Isso pode ser representado por um campo de texto ou relacionado a uma tabela de autores.
</br>-ISBN: O International Standard Book Number é um código único para identificar o livro.
</br>-Quantidade: Quantos 
</br>-Editora: O nome da editora que publicou o livro.
</br>-Ano de Publicação: O ano em que o livro foi publicado.
</br>-Gênero: O gênero literário ao qual o livro pertence (ficção, não ficção, mistério, fantasia, etc.).
</br>-Sinopse: Uma breve descrição do enredo ou conteúdo do livro.
</br>-Classificação: Uma avaliação ou classificação dada ao livro, como uma pontuação de estrelas.
</br>-Quantidade de Páginas: O número total de páginas do livro.
</br>-Idioma: O idioma em que o livro foi escrito.
</br>-Formato: O formato físico ou digital do livro (capa dura, brochura, e-book, etc.).
</br>-Localização Física: Se o livro estiver em uma biblioteca física, pode ser útil registrar onde ele está localizado.
</br>-Data de Aquisição: A data em que o livro foi adquirido.
</br>-Data de Empréstimo: Se o sistema estiver controlando empréstimos, a data em que o livro foi emprestado.
</br>-Data de Devolução: Se o sistema estiver controlando empréstimos, a data esperada de devolução do livro.
</br>-Status de Disponibilidade: Indicador de se o livro está disponível para empréstimo ou não.
</br>-Imagem da Capa: Um link para uma imagem da capa do livro.
</br>}
</br></br></br>
</br> Integração com API de para obter informações sobre os livros. Opções: Google Books API, Open Library API;
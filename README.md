# Bíblia em XML
Este projeto tem o objetivo de democratizar o acesso à Bíblia Sagrada em português brasileiro a programadores, desenvolvedores e pessoas interessadas em proclamar o Evangelho e as boas-novas do Reino de Deus por meio da tecnologia.

## Descrição
Atualmente o projeto conta com três versões da Bíblia Sagrada em Português Brasileiro (pt-BR):
- Nova Versão Internacional (NVI)
- Almeida Corrigida e Fiel (ACF)
- Almeida Revisada Imprensa Bíblica (AA)

As versões estão disponibilizadas em dois formatos:
- XML
- SQL

### XML
Há um arquivo XML para cada versão descrita acima. Os arquivos XML estão codificados em UTF-8 e possuem a seguinte estrutura:
```
<book>
  <chapter>
    <verse>Texto</verse>
  </chapter>
</book>
```

### SQL
Há um arquivo SQL para cada versão descrita acima. Os arquivos SQL estão codificados em UTF-8 e possuem a seguinte estrutura:
- Cria a tabela 'testament'
- Cria a tabela 'books'
- Popula as duas tabelas
- Cria a tabela 'verses'
- Popula a tabela com os versículos

A tabela 'verses' está estruturada da seguinte forma:
- id: é o identificador único do versículo
- version: é a versão da Bíblia (NVI, ACF, AA, etc)
- testament: é a identificação do testamento, (1) Velho Testamento ou (2) Novo Testamento
- book: é a identificação do livro da Bília (1-66)
- chapter: é o número do caítulo
- verse: é o número do versículo
- text: é o texto do versículo

## Metodologia
A compilação dos arquivos foi obtida por meio do crawling de páginas web. Sendo assim, é possível, embora pouco provável, que haja pequenos erros de coleta.

## Licença
As traduções bíblicas deste projeto são de autoria e propriedade intelectual da Sociedade Bíblica Internacional (NVI), da Sociedade Bíblica Trinitariana (ACF) e da Imprensa Bíblica Brasileira (AA). Todos os direitos reservados aos autores.

# Bíblia em XML
Este projeto tem o objetivo de democratizar o acesso à Bíblia Sagrada em português brasileiro a programadores, desenvolvedores e pessoas interessadas em proclamar o Evangelho e as boas-novas do Reino de Deus por meio da tecnologia.

## Descrição
Atualmente o projeto conta com três versões da Bíblia Sagrada em Português Brasileiro (pt-BR):
- Nova Versão Internacional (NVI)
- Almeida Corrigida e Fiel (ACF)
- Almeida Revisada Imprensa Bíblica (AA)

As versões estão disponibilizadas em arquivos XML em codificação UTF-8, um arquivo para cada livro. Cada arquivo possui a seguinte estrutura:
```
<livro>
  <capitulo>
    <versiculo>Texto</versiculo>
  </capitulo>
</livro>
```

## Metodologia
A compilação dos arquivos foi obtida por meio do crawling de páginas web. Sendo assim, é possível, embora pouco provável, que haja pequenos erros de coleta.

## Licença
As traduções bíblicas deste projeto são de autoria e propriedade intelectual da Sociedade Bíblica Internacional (NVI), da Sociedade Bíblica Trinitariana (ACF) e da Imprensa Bíblica Brasileira (AA). Todos os direitos reservados aos autores.

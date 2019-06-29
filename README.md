# Introdução

## Problema a ser solucionado
  Identificação de visemas. Visemas são formatos que a região da boca de um humanóide realiza ao pronunciar fonemas.

## Solução
  Minha proposta é criar um modelo para realizar a identificação destes visemas.

## Beneficiados com a solução
  Atualmente, no mercado de desenvolvimento de animações de modelos 3D há um grande empenho para identificar os visemas para aumentar a velocidade de produção de animações labiais de modelos 3D humanóides. Desta forma, este projeto busca contribuir nessa grande área de estudo com uma  abordagem partindo do ponto de vista de métodos e técnicas do deep learning para a identificação destes visemas. 

# Desafios deste projeto

1) Realizar classificação de imagens em 2 dimensões
2) Lidar com a baixa quantidade de dataset catalagado
3) Criar um modelo que tenha acurárica maior ou igual a 90%

# Resultados obtidos e Lições aprendidas

Como há uma escassa base de dados de visemas disponíveis, foi adotada a seguinte estratégia:
Classificação de dois principais visemas lábios abertos e fechados. Com essas duas categorias já é suficiente para definir marcos temporais para saber se o modelo 3D em sua devida animação deveria estar com a boca aberta ou fechada e salvar essas informações em um metadado para auxiliar na animação dos visemas de modelos 3D animados por computador. Porém, não é suficiente para que haja um total detalhamento de qual visema deve ser modelado.

O resultado concretzido neste trabalho está apresentados no notebook: mouth_classification.

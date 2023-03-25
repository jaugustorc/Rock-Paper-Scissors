# Jogo de Pedra, Papel e Tesoura com Classificação de Imagem usando IA

Este projeto consiste em um jogo de pedra, papel e tesoura, que utiliza inteligência artificial para classificar as imagens dos gestos de mão do usuário em pedra, papel ou tesoura. O jogo utiliza a webcam do usuário para capturar as imagens e, em seguida, o modelo de IA classifica qual movimento foi feito pelo usuário. Em seguida, o computador escolhe aleatoriamente um movimento e é determinado quem venceu o jogo. 

O projeto é implementado em Python, utilizando a biblioteca TensorFlow para o treinamento do modelo de IA. Além disso, é utilizado o Streamlit para criar a interface web para rodar o modelo. O objetivo final do projeto é colocá-lo em produção em uma plataforma em nuvem, como o Heroku, para que possa ser acessado por qualquer pessoa.

## Pré-requisitos

Antes de rodar o jogo, é necessário ter as seguintes dependências instaladas:

- Python 3
- TensorFlow
- OpenCV
- Streamlit

As dependências podem ser instaladas utilizando o gerenciador de pacotes pip.

## Como rodar o jogo

Para rodar o jogo, basta seguir os seguintes passos:

1. Clone este repositório para o seu computador.
2. Instale as dependências utilizando o comando `pip install -r requirements.txt`
3. Rode o jogo utilizando o comando `streamlit run game.py`
4. Abra o navegador e acesse o endereço `http://localhost:8501`

## Como treinar o modelo de IA

Caso você queira treinar o modelo de IA novamente, basta seguir os seguintes passos:

1. Colete um conjunto de dados de imagens de gestos de mão para as três classes: pedra, papel e tesoura.
2. Organize as imagens em pastas separadas para cada classe.
3. Utilize o script `train_model.py` para treinar o modelo de IA. Certifique-se de configurar corretamente o caminho das pastas de treinamento e validação no script.

## Próximos passos

Os próximos passos para o projeto incluem:

- Melhorar o desempenho do modelo de IA através da coleta de mais dados de treinamento e ajuste de hiperparâmetros.
- Aumentar a interatividade do jogo com o usuário através de gráficos e animações.
- Colocar o projeto em produção em uma plataforma em nuvem, como o Heroku.

## Autor

- José Augusto Carvalho

## Licença

Este projeto é licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais detalhes.

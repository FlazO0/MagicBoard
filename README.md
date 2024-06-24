# Lousa Mágica

### Visão Geral do Projeto

Este projeto é uma lousa mágica que permite aos usuários desenhar na tela usando gestos de mão. Utiliza a biblioteca OpenCV e o módulo HandDetector do cvzone para a detecção de mãos e desenho na tela.

### Funcionalidades

- Desenhar na tela usando o dedo indicador.
- Limpar a tela com um gesto específico (levantar três dedos).
- Reconhecimento e resposta em tempo real a gestos de mão.

### Tecnologias Utilizadas

- **Python:** Linguagem de programação principal do projeto.
- **OpenCV:** Biblioteca para processamento de imagens.
- **cvzone:** Biblioteca que facilita a detecção de mãos e manipulação de imagens.

### Configuração e Instalação

#### Requisitos

- Python 3.7 ou superior
- OpenCV
- cvzone

#### Clone o Repositório

```bash
git clone https://github.com/FlazO0/MagicBoard.git
cd MagicBoard
```

#### Instale as Dependências

Certifique-se de ter o Python instalado. Em seguida, instale os pacotes necessários:

```bash
pip install opencv-python cvzone mediapipe
```

### Uso

1. Certifique-se de que a câmera do seu computador está funcionando.
2. Execute o script Python:

    ```bash
    python app.py
    ```

3. Permita o acesso à sua câmera.
4. Use gestos de mão para desenhar na tela:
    - Levante apenas o dedo indicador para desenhar.
    - Levante três dedos (indicador, médio e anelar) para limpar a tela.


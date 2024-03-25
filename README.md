# Sistema de Reconhecimento de Expressões Faciais utilizando I.A.

Projeto da Disciplina de Topicos especiais de engenharia de software(Redes Neurais) - 2023.2

Este é um sistema de reconhecimento de expressões fasciais / emoções desenvolvido em Python utilizando OpenCV. O sistema utiliza técnicas de Processamento de Imagem e Machine Learning para identificar diferentes tipos de expressões faciais em uma imagem.

## Funcionalidades Principais

- **Identificação de Emoções**: O sistema é capaz de analisar imagens contendo rostos humanos e encaixar a expressão da pessoa dentro de 7 possíveis emoções: Raiva; Medo; Feliz; Triste; Surpreso; Nojo; Neutro.

- **Processamento de Imagem**: Utilizando OpenCV, o sistema realiza o pré-processamento das imagens, destacando o rosto humano e classificando-o dentro das 7 classes pré-determinadas.

- **Modelo de Machine Learning**: O sistema utiliza um modelo de Machine Learning treinado previamente para reconhecimento de expressões faciais. Este modelo foi treinado com uma variedade de imagens de diferentes tipos de expressões.

## Requisitos de Sistema

- Python 3.x
- OpenCV
- Bibliotecas Python: NumPy, scikit-learn, etc. (detalhes podem ser encontrados no arquivo requirements.txt)

## Instalação

1. Clone o repositório do GitHub:

```bash
git clone https://github.com/ClassNeuralNetwork/Reconhecimento_de_expressoes.git
```

2. Navegue até o diretório do projeto:

```bash
cd Reconhecimento_de_expressoes
```

3. Instale as dependências usando pip:

```bash
pip install -r requirements.txt
```

## Uso

1. Execute o script principal do sistema:

```bash
python main.py
```

// A FAZER

## Contribuição

Contribuições são bem-vindas! Se você quiser contribuir para este projeto, por favor, abra uma issue para discutir as mudanças propostas ou envie um pull request.
## Equipe
<table align="center">
  <tr>    
    <td align="center">
      <a href="https://github.com/nicolinhaaaaaaas">
        <img src="https://avatars.githubusercontent.com/u/112559599?v=4" 
        width="120px;"  alt="Foto de Nicolas Emanuel no GitHub"/><br>
        <sub>
          <b>Nicolas Emanuel</b>
         </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/thiagoluann">
        <img src="https://avatars.githubusercontent.com/u/112329988?v=4" 
        width="120px;" alt="Foto de Thiago Luan no GitHub"/><br>
        <sub>
          <b>Thiago Luan</b>
         </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/GatoAmarelo">
        <img src="https://avatars.githubusercontent.com/u/111796062?v=4" 
        width="120px;" alt="Foto de Anabel Marinho no GitHub"/><br>
        <sub>
          <b>Anabel Marinho</b>
         </sub>
      </a>
    </td>
  </tr>
</table>

<p align="center">
Cada contribuidor desempenhou um papel essencial no desenvolvimento e aprimoramento deste projeto.
</p>



## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT). Consulte o arquivo `LICENSE` para obter mais detalhes.

## Agradecimentos

Agradecemos aos desenvolvedores e à comunidade de código aberto que contribuíram com ferramentas como OpenCV e scikit-learn, que tornaram possível o desenvolvimento deste sistema de identificação de Expressões Faciais.
@@ -65,4 +110,3 @@ Este projeto está licenciado sob a [Licença MIT](https://opensource.org/license)

# 🤖 Sistema de Reconhecimento Facial com Python e Google Colab

Este projeto implementa um sistema de **detecção e reconhecimento facial** utilizando as bibliotecas `face_recognition`, `OpenCV` e `TensorFlow`, 
rodando diretamente no **Google Colab**. O sistema é capaz de identificar múltiplas pessoas em uma imagem, comparando com imagens de referência previamente cadastradas.

---

## 📌 Funcionalidades

- Detecção automática de rostos em imagens
- Reconhecimento facial com base em imagens de referência
- Suporte a múltiplas pessoas por imagem
- Interface simples via notebook no Google Colab

---

## 🚀 Como usar

### 1. Abra o notebook no Google Colab
Baixe ou abra o notebook `Reconhecimento_Facial_Colab.ipynb` no Google Colab:

[🔗 Acesse pelo Google Colab](https://colab.research.google.com)

---

 Faça o upload das imagens de referência
As imagens devem conter apenas uma pessoa cada.

Nomeie o arquivo com o nome da pessoa, por exemplo:

joao.jpg

maria.png

O código criará automaticamente uma pasta referencias/ para armazená-las.

### 2. Instale as dependências
O notebook já inclui as instruções para instalar as bibliotecas necessárias:
```python
!pip install face_recognition opencv-python tensorflow

Faça upload da imagem de teste
Envie uma imagem com uma ou mais pessoas.

O sistema detectará os rostos e tentará reconhecer com base nas imagens de referência.

🖼 Exemplo de Reconhecimento
Se a imagem grupo.jpg contém João e Maria, e você tem imagens de referência joao.jpg e maria.jpg, o sistema identificará e desenhará os nomes sobre as faces detectadas.

📂 Estrutura esperada de arquivos
Copiar
Editar
📁 referencias/
  ├── joao.jpg
  ├── maria.png
🖼 imagem_teste.jpg
📓 Reconhecimento_Facial_Colab.ipynb
🧠 Tecnologias Utilizadas
Python 3

Google Colab

face_recognition (dlib)

OpenCV

TensorFlow (opcional para expansão)

✅ Sugestão de Expansão
Salvar rostos reconhecidos em banco de dados

Treinar sua própria rede de reconhecimento com TensorFlow ou Keras

Implementar detecção em tempo real com webcam (fora do Colab)

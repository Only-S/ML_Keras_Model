# ML_Keras_Model

> Os arquivos deste repositório são resultado da execução dos passos 1 até o 3.

## Passos para Configuração

1. **Baixar o Dataset:**
   - Acesse: [Kaggle - Cat and Dogs Dataset](https://www.kaggle.com/datasets/d4rklucif3r/cat-and-dogs) (ou outro de sua escolha).

2. **Treinamento do Modelo:**
   - Utilize o [Teachable Machine](https://teachablemachine.withgoogle.com/train/image).
   - Realize o upload das imagens do dataset baixado (é possível fazer o upload de várias imagens de uma vez).
   - Clique em "Train Model".
   - Após o treinamento, teste se o modelo é funcional.

3. **Exportar o Modelo Gerado:**
   - Clique em "Export Model".
   - Selecione a aba "Tensorflow".
   - Escolha "Keras" como tipo de conversão de modelo.
   - Clique em "Download my model".
   - Sob "Code snippets to use your model:", selecione a aba "OpenCV Keras", copie o código fornecido e salve em um arquivo `.py`.

4. **Verificar a Versão do Python:**
   - Caso o Python instalado seja acima da versão 3.10, será necessário realizar o downgrade.
   - Use o comando `python --version` (Windows) ou `python3 --version` (Mac/Linux) para verificar sua versão.
   - Para instalar a versão 3.10 do Python, acesse: [Python 3.10.0](https://www.python.org/ftp/python/3.10.0/) e selecione a versão apropriada para sua máquina.

5. **Instalação de Dependências:**
   - No terminal (Windows), insira:
     ```bash
     pip install tensorflow==2.10
     pip install opencv-python
     ```
   - Caso esteja no Mac/Linux, use:
     ```bash
     pip3 install tensorflow==2.10
     pip3 install opencv-python
     ```

6. **Testar o Modelo:**
   - Execute o código e verifique se a câmera está identificando corretamente as imagens (pode ser necessário permitir o uso da câmera no dispositivo).

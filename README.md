# ML_Keras_Model

(Os passos do 1 ao 3 já foram realizados e se encontram nos arquivos deste repositório)

1. Baixe o datatset do kaggle: https://www.kaggle.com/datasets/d4rklucif3r/cat-and-dogs (ou outro de sua escolha)

2. Realizar o treinamento do modelo, através do Teachable Machine: https://teachablemachine.withgoogle.com/train/image
- Realize o upload das imagens do dataset baixado (pode ser feito o upload de várias imagens de uma vez);
- Clique em "Train Model";
- Após treinado, já é possível testar se o mesmo é funcional.

3. Exportar o modelo gerado:
- Clique em "Export Model";
- Selecione a aba "Tensorflow";
- Model conversion type: Keras;
- Clique em "Download my model";
- Por fim, abaixo de "Code snippets to use your model:" selecione a aba "OpenCV Keras", copie o código fornecido pelo sistema e o salve em algum arquivo ".py".

4. Caso o Python instalado na máquina seja acima da versão 3.10, será necessário realizar o downgrade do mesmo. Use o comando "python --version"(no Windows) ou "python3 --version"(Mac/Linux) para descobrir sua versão.
Para instalar a versão 3.10 do Python, só é possível através do sistema de arquivos do mesmo: https://www.python.org/ftp/python/3.10.0/ (link direto da versão 3.10, selecione a versão apropriada para sua máquina)

5. Após isso, basta instalar o tensorflow e opencv utilizando as linhas de comando a seguir...
No terminal (Windows) insira respectivamente:
pip install tensorflow==2.10
pip install opencv-python

(Caso esteja no Mac/Linux vai ser)
pip3 install tensorflow==2.10
pip3 install opencv-python

6. Agora basta testar se tudo funcionou e ao rodar o código a camêra está identificado corretamente as imagens (talvez seja necessário permitir a utilização da câmera no dispositivo).

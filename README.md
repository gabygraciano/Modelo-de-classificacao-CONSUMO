# Previsão de Consumo - Aplicativo de Gamificação de Shopping 🛍️

## 🔍 Descrição
Este projeto utiliza aprendizado de máquina para prever o tipo de consumo de clientes com base em suas características, otimizando campanhas de marketing dentro de um aplicativo de gamificação de um shopping.

## 📝 Como Funciona:

O modelo de Machine Learning treinado (Random Forest Classifier) utiliza dados como faixa etária, motivo da visita, tipos de lojas frequentadas, fatores de compra e preferência de marcas para prever o tipo de consumo de um cliente com base no e-mail fornecido. O resultado da previsão é exibido em uma interface gráfica simples usando Tkinter.

Esses dados são previamente coletados através de uma pesquisa dentro do aplicativo de gamificação no qual o usuário ganhará pontos por responde-la. As perguntas da pesquisa são pensadas em uma forma que colete os dados que queremos para usar no nosso modelo.

## ⚙️ Tecnologias Utilizadas:

🐍 Python
🐼 Pandas
🧠 Scikit-learn
🖼️ Tkinter

## Como Rodar o Projeto 🏃

### Passo 1: Clone o repositório

   ```bash
   git clone https://github.com/seu_usuario/nome_do_repositorio.git
```

### Passo 2: Instale as dependências

  ```bash
 pip install pandas scikit-learn
```

### Passo 3: Digite o comando abaixo no seu terminal

  ```bash
python app.py
```

## 👨‍💻 Testando o modelo:

### No espaço abaixo, insira um e-mail cadastrado na planilha de dados:

![image](https://github.com/user-attachments/assets/55a479a6-ae66-4586-a189-07540edd9d91)

### Depois é só clicar em "prever" e visualizar o resultado:

![image](https://github.com/user-attachments/assets/4a1d479e-f511-4cb0-be83-bad9e0efe300)


## 📈 Acurácia:

A acurácia do modelo foi calculada em 81%. Esta métrica foi obtida fazendo previsões no conjunto de teste e comparando-as com os rótulos reais.

![image](https://github.com/user-attachments/assets/d9a3487b-60e9-4f76-9d09-f94fc0b69213)





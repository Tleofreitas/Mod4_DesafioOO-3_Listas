# Projeto Contribuintes - Capítulo: Memória, vetores, listas
## Desafio proposto
Para calcular o imposto de renda que uma pessoa deve pagar, um país aplica as seguintes regras:
1) Imposto sobre salário: a pessoa paga imposto sobre seu salário conforme tabela abaixo:

![image](https://user-images.githubusercontent.com/88738577/210085933-5de3c310-ab1a-47c2-9382-6e051f86cf76.png)

2) Se a pessoa obteve renda com prestação de serviços, o imposto cobrado é de 15%.

3) Se a pessoa obteve ganho de capital (imóveis, ações, etc.), o imposto cobrado é de 20%.

4) A pessoa pode abater até 30% do seu imposto bruto devido com gastos médicos ou educacionais. Mas se seus gastos médicos e educacionais forem abaixo desses 30%, 
apenas os gastos médicos e educacionais podem ser abatidos.

Você deve fazer um programa para ler os dados de N contribuintes, armazenando os dados desses contribuintes em uma lista. Depois, você deve mostrar, para
cada contribuinte, um resumo do imposto conforme exemplo abaixo. 

Você deve utilizar uma classe TaxPayer conforme projeto ao lado para representar cada contribuinte. Repare que sua lista vai ter que ser uma List < TaxPayer> 

Lembre-se de respeitar os nomes apresentados no projeto ao lado (como foi fornecido o projeto para você executar, você tem que respeitar a especificação do projeto).

Sinta-se livre para implementar construtores pra facilitar a instanciação dos objetos.

![image](https://user-images.githubusercontent.com/88738577/210086288-3731d97c-34a8-475d-b42a-57a1a528cc24.png)

---
EXEMPLO: <br>
Quantos contribuintes você vai digitar? 2 <br>
Digite os dados do 1o contribuinte: <br>
Renda anual com salário: 48000.00 <br>
Renda anual com prestação de serviço: 0.00 <br>
Renda anual com ganho de capital: 800.00 <br>
Gastos médicos: 400.00 <br>
Gastos educacionais: 5400.00 <br>

Digite os dados do 2o contribuinte: <br>
Renda anual com salário: 189000.00 <br>
Renda anual com prestação de serviço: 55184.93 <br>
Renda anual com ganho de capital: 20000.00 <br>
Gastos médicos: 600.00 <br>
Gastos educacionais: 7500.00 <br>

*Resultado esperado* <br>
Resumo do 1o contribuinte: <br>
Imposto bruto total: 4960.00 <br>
Abatimento: 1488.00 <br>
Imposto devido: 3472.00 <br>

Resumo do 2o contribuinte: <br>
Imposto bruto total: 50077.74 <br>
Abatimento: 8100.00 <br>
Imposto devido: 41977.74 <br>


Sexo: F <br>

---
## *Realizando teste do código localmente* 
O Windows 10 já possui um programa padrão para visualizar arquivos compactados.

Caso seu sistema operacional seja anterior ao Windos 10, realize o passo abaixo:

Para visualizar o projeto você precisará extrair os arquivos através de um programa para arquivos compactados.

Recomendo Winrar, baixe a versão 32x ou 64x, de acordo com seu sistema.

Link para download:
https://www.win-rar.com/download.html

---
## 📦️ *Como Testar o Código*
Para executar este passo, você tera que ter uma IDE instalada em sua máquina. Utilizei o Eclipse.


Siga o passo a passo abaixo:
```bash
  # Clone o repositório
  ❯ Clique no botão Code, depois em Download ZIP e salve o arquivo.

  # Extrair arquivos sem Winrar
  > Abra a pasta onde o arquivo foi salvo.
  >> Clique com o botão direito sobre o arquivo e selecione
  Extrair Tudo.
  As informações foram extraídas para a pasta Mod4_DesafioOO-3_Listas-main.

  # Extrair arquivos com Winrar
  > Abra a pasta onde o arquivo foi salvo.
  >> Clique com o botão direito sobre o arquivo e selecione Extrair Aqui (Extract Here).
  As informações foram extraídas para a pasta Mod4_DesafioOO-3_Listas-main.
  
  # Abrir o projeto
  > No Eclipse, clique em *File* e após em *Open Projects from File System...*
  >> Selecione a pasta do projeto e depois clique em *Finish*
  Aguarde a IDE carregar os arquivos e então visualize o código fonte.
  
```

---
## ⚠️ *Erros comuns* ⚠️

No passo *Como Testar o Código*, se não houver a opção *Extrair Tudo*, significa que não há programa instalado para manipulação de arquivos compactados.
Neste cado, seguir com o passo *Realizando teste do código localmente*.

No passo *Abrir o projeto*, após os arquivos serem carregados, pode acontecer de aparecer um X ou um ! vermelho. Caso isso ocorra, tente as soluções deste
tutorial: https://www.youtube.com/watch?v=Je4JWWJcyo0

---
## *Contribuidores* 🔥👊
Este projeto foi desenvolvido durante o curso Formação Desenvolvedor Moderno da escola [@DevSuperior](https://devsuperior.com.br), sobe orientação do tutor [Nelio Alves](https://www.linkedin.com/in/nelio-alves/?originalSubdomain=br).




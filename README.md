#Projeto IA900 -Aprevisão de Alugueis de B0icicletas
* Passo 1: Criar um workspace do azure e iniciar o ML Azure Studio
* Passo 2: Crie um Job Automatizado
* Passo 3: Congiurações basicas
* Configurações básicas :

  Nome do trabalho : mslearn-bike-automl
  Novo nome do experimento : mslearn-bike-rental
  Descrição : Aprendizado de máquina automatizado para previsão de aluguel de bicicletas
  Marcadores : nenhum
  Tipo de Tarefa: Regressão
Passo 4: Crie um conjunto de dados
Passo 5: Após criar um conjunto de dados, selecione o conjunto de dados para continuar a tarefa.
Passo 6: Enviar o trabalho para treinamento
Passo 7: Testar modelo
  *clicar em implantar
  *Nome : prever-aluguéis
  Descrição : Prever aluguel de bicicletas
  Tipo de computação : Instância de Contêiner do Azure
  Habilitar autenticação : selecionado
Passo 8: Testar serviço implantado
  * clcar no botao testar
  * copiar os dados de teste
  *  {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 
  }

  ** clicar no botao testar** para veriicar as predições do sue modelo
  
  

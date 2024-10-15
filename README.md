# Step Functions
Essa atividade utiliza a ferramenta chamada Step Functions da AWS.

### Resumo sobre a ferramenta
Essa ferramenta permite criar Workflows visuais e por meio de código para orquestrar microserviços, automatizar processos, criar pipelines de dados...
A automatização pode ser feita com a integração de mais de 200 produtos da AWS de forma fácil, por meio de uma simples interface de blocos ou por meio de linguagem de programação chamada ASL (baseada em JSON).
O custo e precificação da ferramenta é de acordo com cada serviço utilizado. Por exemplo: se for utilizado em um passo uma consulta de prompt via Amazon Bedrock, será contabilizado o modelo LLM utilizado e a quantidade de tokens utilizados.

---

# Atividade
Segue junto nesse projeto um arquivo do tipo [JSON](https://github.com/WallaceWyslas/dio-EngenhariaPrompt-Projeto2/blob/main/code.json), onde:
- foi criada uma Step Function com base no Demo Bedrock;
- liberou o acesso da ferramenta às políticas do Amazon Bedrock;
- setou a ferramenta para o uso da LLM Haiku;
- Adaptou o código para uma pessoa que deseja fazer academia, e o prompt vai alterando automaticamente, conforme sua necessidade.
![image](https://github.com/user-attachments/assets/112f31a4-0232-49fe-ac34-09176063ead8)

### Prompts utilizados
A seguir, encontra-se o que foi pedido em cada prompt:
1. Com base na variável prompt1, estipule a capacidade da pessoa de praticar exercícios e qual o seu objetivo;
2. De acordo com o prompt2, crie uma lista de exercícios para se praticar durante uma semana, com base na atividade pedida;
3. Com base no prompt3, adapte a lista de exercícios para a pessoa, com base nas suas restrições.

### Variáveis utilizadas para obtenção do resultado
```json
{
  "prompt1": "Sou um homem de 20 anos, que nunca praticou exercícios na vida e que gostaria de começar. Meu principal objetivo é ser saudável e não desenvolver doenças causadas pelo sedentarismo",
  "prompt2": "Desejo praticar exercícios 3x na semana, em uma academia, com maquinário",
  "prompt3": "Descobri que minha massa gorda está alta e que tenho burcite no ombro direito"
}
```


### Resultado
Como eu não tenho acesso aos modelos Amazon Bedrock, não obtive resultado.

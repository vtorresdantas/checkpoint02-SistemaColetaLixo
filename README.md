# Checkpoint02 - Sistema de coleta de lixo

*AVALIAÇÃO DE ACOMPANHAMENTO – 1º SEMESTRE – ENGENHARIA DE SOFTWARE* 

Uma empresa de coleta seletiva de lixo precisa de um sistema para melhorar a programação
de coleta de seus caminhões e assim, reduzir os custos operacionais, já que as suas operações
têm margens de lucro muito pequenas e a eficiência em custos é diretamente responsável pela
continuidade e evolução do negócio.
 
 Essa empresa deseja ter um sistema de informação que permita planejar rotas de coleta com
base na verificação em tempo real das condições de tráfego, dado um plano de ruas a percorrer
por cada caminhão. Os caminhões também devem ser geograficamente localizados para que se
verifique remotamente a movimentação do mesmo.
 
 Cada caminhão de coleta de lixo tem uma tonelagem de capacidade e terá uma determinação
de quais ruas da cidade percorrerá, com base no histórico de geração de lixo de cada uma delas.
Esse histórico é informado pelo caminhoneiro ao retornar à empresa de coleta com o caminhão
cheio ou parcialmente cheio – se ficou lixo para trás, devido ao caminhão ter esgotado a sua
capacidade, um outro caminhão precisa ser enviado à rua com coleta incompleta e a quantidade
total de lixo coletado no caminho é guardada no sistema (toneladas de lixo por rua) para que o
planejamento de futuras coletas programe a quantidade correta de caminhões.
 
 Você é um profissional full stack de TI da empresa de coleta e será responsável por planejar o
desenvolvimento do software.
 
 É importante considerar que o proprietário da empresa de coleta, que é o seu chefe direto,
ainda não tem claro se precisará de outros recursos no sistema de informação, além dos
relatados anteriormente. Ele precisa que você e os demais membros da equipe sejam flexíveis
quanto à possibilidade de mudanças de escopo. Além disso, o dono da empresa quer que você
entregue o quanto antes algum recurso para ele usar, seja a avaliação do estado do trânsito na
rota, a geolocalização, o apontamento de lixo coletado, ou outra funcionalidade. 

# QUESTÕES AVALIATIVAS: 

*1ª (peso 2,0):* Crie um mapa mental que associe os recursos que o sistema deve oferecer para
fazer a programação de saída de veículos para coletar lixo. Inclua os cadastros básicos de dados
que são necessários para operar a coleta como Ruas, Caminhões, etc. SALVE O DESENHO EM
FORMATO PDF COM O NOME *MapaMental.PDF.*

Critério de avaliação (1 ponto cada item):

- Nó central do mapa de decisão correto, contendo o objetivo principal a ser atingido;
- Associações com o nó central representam operações necessárias para alcançar o objetivo. 

# MapaMental

![image](https://user-images.githubusercontent.com/62342894/163173590-4cc374ce-eddb-4a33-bf9b-bffcd244c57e.png)

*2ª (peso 6,0):* Desenhe o fluxo de processo (COM UMA FERRAMENTA DA SUA ESCOLHA) que
representa a programação e disparo do envio de caminhões para coleta e todo o controle de
movimentação e retorno dos caminhões, contemplando as etapas descritas no texto,
imaginando o cenário TO BE (como vai ser quando o sistema de gerenciamento estiver
implantado). Não se preocupe em registrar as atividades de cadastramento de dados básicos
como ruas, caminhões, motoristas, equipes de coleta – considere que tudo isso já foi cadastrado
e foque em explicar os passos para programar a saída do caminhão, monitorar o andamento da
coleta e seu resultado. Imagine que existem duas áreas diferentes na empresa que estão 
envolvidas com as atividades: Área de roteirização de coletas (que planeja o envio de caminhões
com motoristas alocados e define os trajetos nas ruas); Área de execução de coletas (que
acompanha o movimento dos caminhões nas ruas e monitora o apontamento da descarga de
lixo ao retornar à sede da empresa). Coloque atividades no seu fluxo que representam
operações que o futuro sistema de informação terá que executar (registros de saída e retorno
de veículos por exemplo, entre outras). SALVE O DESENHO EM FORMATO PDF COM O
NOME MapaProcesso.PDF! Seu mapa de processo deve contem APENAS AS OPERAÇÕES QUE
SERÃO FEITAS VIA SOFTWARE/SISTEMA DE INFORMAÇÃO! 

Critério de avaliação (1 ponto cada item):

- Uso de raias para separar os departamentos/usuários responsáveis pelas operações;
- Uso correto de marcadores de início e fim de fluxo de processo;
- Uso correto de decisões/gateways de desvio de fluxo em razão da lógica de negócio;
- Uso correto de tarefas para representar as atividades que o usuário fará no sistema quando ele
estiver pronto, com o intuito de planejar a cólera de lixo;
- Uso de repositórios de dados associados às tarefas para representar os pontos onde dados serão
coletados e/ou consumidos (usados);
- Uso de comentários associados aos depósitos de dados para explicar os dados que serão
guardados em cada repositório

# MapaProcesso

![image](https://user-images.githubusercontent.com/62342894/163173666-ac5934fb-7444-4255-b400-14635b5eb382.png)

*3ª (peso 2,0):* Crie um REPOSITÓRIO PÚBLICO no GITHUB e suba os dois arquivos em uma pasta
chamada LevantamentoRequisitos que você vai criar em uma Branch Develop.
Critério de avaliação (1 pontos cada item):

- Criação do repositório público com a branch Develop;
- Criação da pasta LevantamentoRequisitos, contendo os arquivos MapaProcesso.PDF e MapaMental.PDF. 

https://github.com/vtorresdantas/checkpoint02-SistemaColetaLixo/tree/develop

















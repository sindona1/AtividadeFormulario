# Atividade Formulario
Formulário para atividade FMU

O formulário foi criado tendo em vista a necessidade de ter um *reminder* para quando fosse aberta a pré-venda de ingressos para jogos da NFL no Brasil, por sem um evento não tão comum de acontecer no brasil, os ingressos para o kick off da temporada 24/25 na Neo Química Arena se esgotaram em pouquissimas horas e diversos torcedores do esporte não puderam ir ao jogo por terem perdido as datas/horários de venda dos ingressos. O nosso site tem a intenção de enviar um lembrete para o torcedor de não perder as datas de venda dos ingressos e dos jogos.

Todos os campos presentes dentro do formulário são obrigatórios, porém a primary key para que não haja mais de um cadastro por pessoa é o campo CPF, que permite o controle de entrada dentro do banco de dados de apenas CPFs únicos. Os demais campos são de extrema importância para coleta e análise de dados dos torcedores

O projeto foi desenvolvido em três partes, a primeira sendo o brainstorm para decidir o tema do projeto, reunindo ideias dos participantes do grupo com o intuito de encontrar um denominador em comum para todos. Em seguida seguimos para o sketch e montagem do UI do site através do software Figma, onde contamos com outro brainstorm para novamente entrar num denominador em comum de como visualizamos nosso site(as imagens do sketch estão presentes dentro da pasta "*sketch UI*") e por fim, na terceira etapa foi feito a "codagem" do site que apresenta duas telas para o cliente final, porém foi separada em 3 telas de código:

- index.html: Tela onde será apresentado o formulário para o cliente final preencher e realizar o envio dos seus dados, foram utilizados inputs do tipo text, email, date e checkbox além de um botão do tipo submit indexado com um metodo *POST* para envio desses dados para o banco de dados(Será criado nas próximas etapas do projeto)
- confirmacao.html: Tela contendo uma mensagem de agradecimento ao torcedor que acabou de enviar seus dados para futuramente ser contactado com as datas dos jogos e da pré-venda dos ingressos
- estilo.css: Tela que comanda todas as características visuais presentes no formulário

Nosso projeto até o momento não contempla diretrizes de limitação de caracteres, condições dependentes de checkboxes ou obrigatoriedade de campos para o envio do formulário, porém esperamos nas próximas etapas junto com a criação de um banco de dados, limitar os caractéres, realizar a validação de formatos e criar essas condições dependentes para caso não preenchido o formulário não ser enviado, até o momento temos apenas a validação de formato dentro da data de nascimento do usuário que contempla o seguinte placeholder Dia/Mês/Ano.

Os integrantes do grupo são:

2025589 - Olavo Crispim
2032163 - Augusto Santos Preto
1898835 - Enzo Freitas Sindona
1968864 - Matheus Pereira dos Santos

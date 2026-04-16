***Aluno***

- RF01, RF04, RF05, RF06, RF10

- idAluno

- nome

- cpf

- email

- telefone

- endereco

- rfid

- status

- contratarPlano()

- agendarAula()

- cancelarAgendamento()

- atualizarStatus()

- registrarAcesso()

- receberNotificacao()


***Plano***

- RF01, RF02, RF04

- idPlano

- nome

- tipo

- valor

- ativo

- ativar()

- desativar()

- alterarValor()


***Pagamento***

- RF03, RF04, RF09

- idPagamento

- data

- valor

- formaPagamento

- status

- aplicarCupom()

- parcelar()

- registrar()

- confirmar()

- cancelar()


***Acesso***

- RF05, RF09

- idAcesso

- dataHora

- autorizado

- verificaRegularidade()

- libera()

- bloqueia()


***Aula***

- RF06, RF07, RF09

- idAula

- nome

- horario

- capacidadeMaxima

- cancela()

- alteraStatus()

- registraPresenca()


***Agendamento***

- RF06, RF10

- idAgendamento

- dataReserva

- status

- alteraData()

- cancelaAgenda()

- registraInstrutor()

- reserva()


***Presenca***

- RF07

- idPresenca

- data

- presente

- registra()

- confirma()

- JustificaFalta()


***AvaliacaoFisica***

- RF08, RF10

- idAvaliacao

- data

- peso

- imc

- percentualGordura

- observacoes

- anexo

- vinculaAluno()

- registraRecomendacoes()

- criaPlanodeAula()

- anexarArquivo()


***Notificacao***

- RF10

- idNotificacao

- tipo

- dataEnvio

- status

- mensagem

- enviaAgenda()

- enviaInadimplencia()

- marcarComoLida()


***Instrutor***

- RF07, RF08

- idInstrutor

- nome

- especialidade

- realizaAvaliacaoFisica()

- registraAula()

- AplicaAula()

- registraPresenca()

- consultaAgenda()

- cancelaAgenda()


***Recepcionista***

- RF01, RF03

- idRecepcionista

- nome

- cadastraAluno

- gerenciaAgenda()

- gerenciaAcesso()

- cobraInadimplentes()

- registraPagamento()


***Gerente***

- RF02, RF09

- idGerente

- nome

- cadastraPlanos()

- alteraPlanos()

- alteraAlunos()

- emiteRelatorios()

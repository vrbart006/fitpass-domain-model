### DIAGRAMA EXPLICADO

## 1. Aluno
Representa o cliente da academia.
Contém:
- dados pessoais (nome, CPF, email etc.)
- status (ativo/inativo)
- método verificarRegularidade()

# Tudo gira em torno do aluno.

## 2. Plano
Define o tipo de assinatura do aluno:
- mensal
- trimestral
- anual
- musculação, funcional etc.
# É ligado a MATRÍCULA do ALUNO.

## 3. Matrícula
Aluno + Plano
"quando começou
quando termina
se está ativa"
# Isso é o que define se o aluno está “ativo na academia”

## 4. Pagamento
Registra tudo que o aluno paga:
- dinheiro
- cartão
- PIX
# Importante:
saber se o aluno está regular (RF04)

## 5. Acesso
Representa a entrada na academia (catraca)
- usa RFID
- registra data/hora
- autoriza ou nega entrada
# Aqui está o físico da academia

## 6. Aula
Representa as aulas disponíveis:
- nome da aula
- horário
- capacidade

## 7. Agendamento
É a ligação:
-- Aluno reserva uma Aula

-- Ele resolve o RF06

## 8. Presença
Registra se o aluno realmente compareceu à aula
- usada pelos instrutores

## 9. Instrutor
Responsável por:
- aulas
- avaliações físicas

## 10. Avaliação Física
Registra evolução do aluno:
- peso
- IMC
- gordura corporal
- observações

## 11. Notificação
Sistema envia mensagens automáticas:
- vencimento de mensalidade
- confirmação de aula
- avaliação disponível

## 12. Como tudo se conecta
 # Aluno:
faz matrícula
paga mensalidade
acessa academia
agenda aulas
recebe notificações
 # Plano:
define o tipo de contrato
 Matrícula:
liga aluno ao plano
 # Pagamento:
garante regularidade
 # Aula + Agendamento:
aluno reserva aulas
 # Presença:
confirma participação
 # Instrutor:
ministra aulas e avaliações
 # Avaliação:
acompanha evolução física

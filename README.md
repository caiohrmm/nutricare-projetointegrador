# Nutricare

O Nutricare é uma plataforma web desenvolvida para nutricionistas que desejam gerenciar seus pacientes de forma prática e organizada.
A ferramenta permite o cadastro de pacientes, agendamento de consultas, controle de evolução e criação de planos alimentares personalizados, tudo em um único sistema centralizado.

## Objetivo do Sistema

Facilitar o trabalho dos nutricionistas, oferecendo um painel completo para:
	•	Armazenar e organizar informações dos pacientes
	•	Agendar e controlar consultas
	•	Registrar avaliações físicas e evolução
	•	Criar e atualizar planos alimentares individualizados

O sistema busca otimizar o atendimento nutricional, promovendo um acompanhamento mais eficiente e profissional dos pacientes.

Principais Funcionalidades
	•	Cadastro e gerenciamento de pacientes
	•	Agendamento e visualização de consultas
	•	Registro de dados antropométricos (peso, altura, medidas)
	•	Criação e edição de planos alimentares personalizados
	•	Dashboard de controle geral com resumos e atalhos
	•	Área de perfil para atualização de dados do nutricionista

## Tecnologias Utilizadas

Frontend:
- Angular
- TypeScript

Backend:
- Node.js
- Express.js

Banco de Dados:
- FireBase

1. Tela de Login
	•	Entrar no sistema.
	•	(E-mail + Senha)

⸻

2. Tela de Cadastro do Nutricionista
	•	Nome completo
	•	E-mail
	•	Senha
	•	Número do registro profissional (CRN)
	•	Telefone (opcional)

⸻

3. Tela Principal: Dashboard de Controle

Aqui o nutricionista vê tudo num painel só. O que deve ter:
	•	Resumo rápido:
	•	Número total de pacientes
	•	Consultas agendadas para hoje
	•	Consultas da semana
	•	Pacientes sem consulta agendada
	•	Agenda (calendário de consultas próximas)
	•	Atalhos rápidos:
	•	Botão “Novo Paciente”
	•	Botão “Nova Consulta”
	•	Notificações:
	•	Alertas de consultas próximas
	•	Alertas de planos alimentares a revisar

⸻

4. Tela de Cadastro de Pacientes
	•	Nome do paciente
	•	Data de nascimento
	•	Sexo
	•	Peso inicial
	•	Altura
	•	Objetivo (ex: emagrecer, ganhar massa, saúde)
	•	Observações (histórico médico, alergias)

⸻

5. Tela de Listagem de Pacientes
	•	Tabela com:
	•	Nome
	•	Idade
	•	Objetivo
	•	Última consulta
	•	Próxima consulta
	•	Botão em cada paciente:
	•	“Visualizar Detalhes”
	•	“Nova Consulta”

⸻

6. Tela de Agendamento de Consultas
	•	Escolher paciente
	•	Escolher data e hora
	•	Motivo / Observação da consulta (ex: Retorno, Avaliação inicial)
	•	Botão “Salvar”

⸻

7. Tela de Consulta

(Quando o nutricionista clica em uma consulta marcada)
	•	Dados do paciente
	•	Dados da consulta atual
	•	Área para:
	•	Preencher peso atual
	•	Medidas (circunferência, percentual de gordura, etc.)
	•	Anotações da avaliação
	•	Criar / Atualizar Plano Alimentar

⸻

8. Tela de Planos Alimentares
	•	Selecionar paciente
	•	Cadastrar refeições:
	•	Café da manhã
	•	Lanche da manhã
	•	Almoço
	•	Lanche da tarde
	•	Jantar
	•	Ceia
	•	Lista de alimentos e quantidades
	•	Observações extras (ex: recomendações de água, suplementos)

⸻

9. Tela de Perfil do Nutricionista
	•	Atualizar dados pessoais
	•	Alterar senha


MIT


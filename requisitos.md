---------REQUISITOS FUNCIONAIS (RF)----------

RF01 O usuário deve poder se cadastrar no sistema, criando login e senha 	   

RF02 Uma vez logado, o usuário deve poder marcar consultas por especialidade, local e data disponível	              

RF03 O usuário deve ter acesso a uma seção onde haja dados de pagamentos, boletos a serem pagos e outras informações financeiras 

RF04 O usuário deve ter acesso a uma seção onde possa ser feita a troca de plano	

RF05 O usuário deve poder atualizar seus dados cadastrais e solicitar a troca de senha através do e-mail cadastrado	

RF06 O sistema deve permitir a criação de um perfil de administrador com login e senha para operadores	

RF07 Os administradores do sistema devem poder cadastrar/excluir hospitais, clínicas e médicos particulares, definindo as especialidades e o local de atendimento	

RF08 Os administradores do sistema devem poder realizar alterações nos planos dos usuários através de solicitações previamente enviadas pelos usuários dentro do sistema	

RF09 Após serem cadastrados, sistema deve permitir que clínicas e médicos criem um perfil com login e senha	

RF10 O sistema deve permitir que clínicas e médicos insiram informações de vagas de atendimento, com datas e horários, assim como informações de consultas e exames já realizados (nome do paciente, horário, tipo de exame realizado...).	


----------REQUISITOS NÃO FUNCIONAIS (RNF)-------------

RNF01 Compatibilidade: O sistema deve ser responsivo e funcionar perfeitamente nos principais navegadores (Chrome, Safari, Edge, Firefox) e sistemas operacionais móveis (iOS e Android).

RNF02 Desempenho: O tempo de resposta para a busca de médicos credenciados ou confirmação de agendamento não deve ultrapassar 2 segundos sob condições normais de uso.

RNF03 Disponibilidade: O sistema deve ter alta disponibilidade de 99% em escala de 24/7, com tempo máximo de indisponibilidade de 8,5h por ano

RNF04 Escalabilidade: A arquitetura deve suportar picos de acessos simultâneos de até 4.000 usuários sem declínio do desempenho.

RNF05 Usabilidade e Acessibilidade: A interface web e mobile deve seguir as diretrizes de acessibilidade WCAG 2.1 nível AA.

RNF06 Auditabilidade e Logs: O sistema deve registrar logs imutáveis de todas as operações de criação, leitura, alteração e exclusão (CRUD) de dados pessoais e agendamentos para fins de auditoria.

RNF07 Interoperabilidade: O sistema deve integrar-se com ERPs de planos de saúde e prontuários eletrônicos via APIs RESTful.

RNF08 Recuperabilidade: O tempo de recuperação (RTO) em caso de falha crítica do servidor deve ser inferior a 1 hora.

RNF09 Confiabilidade e Integridade: controle rigoroso de transações (ACID) para impedir o duplo agendamento do mesmo horário para médicos diferentes pelo mesmo usuário.

RNF10 A requisição deve ser criptografada usando protocolo TLS 1.3 e os logs não podem expor dados sensíveis do paciente em texto puro.

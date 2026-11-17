# ⚽ Futfralda da Anasthácia
Convite público e painel privado para o evento de sábado, 28/11/2026 às 18h.
O site está no diretório futfralda-anasthacia. Hospedagem gratuita do Render, independente da aplicação do mandato.
As confirmações são gravadas nas tabelas public.futfralda_anasthacia_rsvps e public.futfralda_anasthacia_admins do Supabase, com RLS.
A inscrição pública pode somente inserir respostas. Apenas os usuários do Supabase Auth cadastrados na tabela de administradores podem ler ou excluir os dados.
Para autorizar o pai: ele deve criar sua conta em painel.html e confirmar o e-mail; então o gestor deve executar INSERT na tabela futfralda_anasthacia_admins com o UUID do usuário registrado. Não colocar credenciais de service_role nos arquivos públicos.
Depois do evento, exportar se necessário e apagar os dados pessoais.

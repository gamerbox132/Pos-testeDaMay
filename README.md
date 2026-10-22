# Pos-testeDaMay
Pós-teste
LEIA ATENTAMENTE AS INSTRUÇÕES!
Você terá 30 minutos para resolver os três cenários.
Não é permitido consultar materiais durante a avaliação, as telas serão monitoradas tanto pelos
monitores quanto pela gravação e pelo monitor de processos que vai ativar um sinal sonoro caso
saia das telas permitidas que são (VScode, Git bash, CMD, plataforma do web academy e GitHub).
Crie um repositório público no GitHub e organize os três cenários em pastas separadas (desafio1,
desafio2 e desafio3). Ao finalizar, envie o link do repositório na plataforma.
Cenário 1 — Ata do clube de leitura
Contexto: Você é secretário(a) de um clube de leitura e ficou responsável por manter o histórico
das atas das reuniões.
Crie uma pasta clube contendo o arquivo ata.txt com a seguinte informação:
Livro do mês: Dom Casmurro
O clube realiza reuniões periódicas, e as informações registradas precisam ser atualizadas sem
perder o histórico das versões anteriores.
Tarefas
1. Adicione o arquivo ao repositório Git e registre sua versão inicial com uma mensagem
adequada.
2. Na reunião seguinte, acrescente a informação Próxima reunião: dia 20 e registre uma nova
versão.
3. Posteriormente, um integrante informou que a próxima reunião acontecerá no dia 25.
Atualize o arquivo, verifique as alterações realizadas e registre a nova versão.
4. A coordenação deseja saber em qual versão a data da reunião foi informada pela primeira
vez. Consulte o histórico e identifique esse registro.
5. A coordenação decidiu manter a data originalmente prevista. Recupere a informação
anterior, preservando o histórico de alterações, e registre a correção.
Cenário 2 — Roteiro de viagem
Contexto: Uma agência de turismo utiliza o arquivo roteiro.txt para manter o roteiro oficial de uma
viagem, composto por três atividades: visita à praia, passeio ao museu e apresentação musical.
A equipe de planejamento decidiu desenvolver uma proposta alternativa, incluindo passeios de
barco e um jantar especial. Entretanto, o roteiro atual continua sendo comercializado e não pode
ser modificado até que a nova proposta seja aprovada.
Durante o desenvolvimento da proposta, a agência também recebeu uma solicitação para atualizar
o roteiro oficial.
Tarefas
1. Crie o arquivo roteiro.txt e registre a versão inicial do roteiro oficial.
2. Crie um ambiente isolado para desenvolver a proposta alternativa, sem modificar o roteiro
utilizado atualmente.
3. Acrescente ao roteiro alternativo um passeio de barco e um jantar especial. Registre as
alterações realizadas.
4. Enquanto a proposta estava em desenvolvimento, a equipe comercial solicitou a inclusão de
uma visita ao centro histórico no roteiro oficial. Realize essa alteração na branch principal e
registre uma nova versão.
5. A diretoria aprovou a proposta alternativa. Integre as alterações, garantindo que o roteiro
final contenha tanto as atividades aprovadas quanto a atualização solicitada pela equipe
comercial.
6. Verifique o resultado da integração e decida o que fazer com a branch utilizada para
desenvolver a proposta alternativa.
Cenário 3 — Regulamento do condomínio
Contexto: Um condomínio utiliza um repositório Git para controlar as alterações do seu
regulamento interno.
O arquivo regulamento.txt contém inicialmente a seguinte regra:
Horário de silêncio: a partir das 22h
Durante uma reunião, duas propostas de alteração foram elaboradas separadamente.
A primeira proposta, apresentada pela administração, altera o horário para:
Horário de silêncio: a partir das 21h
A segunda proposta, apresentada pelo conselho, altera a regra para:
Horário de silêncio: a partir das 23h
As propostas foram desenvolvidas em branches diferentes, a partir da mesma versão original do
regulamento.
Posteriormente, a assembleia decidiu que o horário correto deveria ser 21h30.
Tarefas
1. Crie o arquivo regulamento.txt, registre a versão inicial e prepare duas branches
independentes para as propostas da administração e do conselho.
2. Realize as alterações correspondentes em cada branch e registre as mudanças
separadamente.
3. Integre a proposta da administração à branch principal e, em seguida, tente incorporar a
proposta do conselho.
4. Resolva o conflito entre as alterações, considerando a decisão final da assembleia, e
conclua a integração.
5. Publique o regulamento atualizado no repositório remoto.
6. Após a publicação, a administração percebeu que a decisão de estabelecer o horário às
21h30 foi registrada incorretamente e precisa ser desfeita. Reverta o commit que introduziu
essa decisão sem apagar ou reescrever o histórico já publicado, preservando as demais
alterações válidas.
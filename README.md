db.client_processes.insertMany([
{
  "client_id": "id_do_cliente_maria_silva",
  "number": "PROC-2023-001",
  "value": 1500.00,
  "status": "ativo",
  "class": "Cobrança",
  "description": "Processo de cobrança referente a fatura em aberto.",
  "created_at": ISODate("2023-10-26T10:00:00Z")
},

{
  "client_id": "id_do_cliente_empresa_solucoes",
  "number": "PROC-2023-002",
  "value": 5500.50,
  "status": "em análise",
  "class": "Contratual",
  "description": "Análise de contrato de prestação de serviços.",
  "created_at": ISODate("2023-11-15T14:30:00Z")
}]);

db["client_processes"].find()
{
  _id: ObjectId('6809890ca70b53bfa65b9f67'),
  client_id: 'id_do_cliente_maria_silva',
  number: 'PROC-2023-001',
  value: 1500,
  status: 'ativo',
  class: 'Cobrança',
  description: 'Processo de cobrança referente a fatura em aberto.',
  created_at: 2023-10-26T10:00:00.000Z
}
{
  _id: ObjectId('6809890ca70b53bfa65b9f68'),
  client_id: 'id_do_cliente_empresa_solucoes',
  number: 'PROC-2023-002',
  value: 5500.5,
  status: 'em análise',
  class: 'Contratual',
  description: 'Análise de contrato de prestação de serviços.',
  created_at: 2023-11-15T14:30:00.000Z



  db["events"].find()

  {
  _id: ObjectId('68098870cd9d976e3040ca00'),
  client_id: 'id_do_cliente_maria_silva',
  enterprise: null,
  cnpj_enterprise: null,
  freight: 50,
  amount_of_cleaning: 2,
  cleaning_date: '2023-12-10',
  cost_of_each_cleanin: 200,
  proposal_doc: 'PROP-MS-001.pdf',
  number_proposal: 'PROP-2023-001-MS',
  proposal_expiration_date: 2023-11-30T23:59:59.000Z,
  created_proposal_by: 'user_id_do_sales_3',
  address: 'Rua das Camélias, 789',
  city: 'São Paulo',
  state: 'SP',
  zip_code: '02002000',
  proposal_status: 'accepted'

    _id: ObjectId('68098870cd9d976e3040ca01'),
  client_id: 'id_do_cliente_empresa_solucoes',
  enterprise: 'Soluções Ltda',
  cnpj_enterprise: '12345678000190',
  freight: 120,
  amount_of_cleaning: 5,
  cleaning_date: '2024-01-15',
  cost_of_each_cleanin: 150,
  proposal_doc: 'PROP-ESL-002.pdf',
  number_proposal: 'PROP-2023-002-ESL',
  proposal_expiration_date: 2023-12-20T23:59:59.000Z,
  created_proposal_by: 'user_id_do_sales_3',
  address: 'Avenida das Palmeiras, 1011',
  city: 'Rio de Janeiro',
  state: 'RJ',
  zip_code: '22020030',
  proposal_status: 'pending accepted'

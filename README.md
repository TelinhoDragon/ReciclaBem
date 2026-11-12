# ReciclaBem
Aplicativo que ensina a reciclar corretamente, mostra os pontos de coleta mais próximos e informa os horários de passagem dos caminhões de lixo na cidade de São Paulo e região metropolitana.

📑 Sumário
Sobre o projeto
Problema e objetivo
Funcionalidades
Alinhamento com os ODS
Tecnologias utilizadas
Estrutura do projeto
Como executar
Fontes de dados
Roadmap
Como contribuir
Equipe
Licença

📱 Sobre o projeto

O ReciclaBem é um aplicativo desenvolvido por estudantes da Fatec Barueri como projeto acadêmico. O objetivo é facilitar o descarte correto de resíduos, aproximando o cidadão das práticas de reciclagem por meio da tecnologia.

O foco principal é a cidade de São Paulo e região metropolitana, uma das maiores áreas urbanas do mundo e, consequentemente, com um dos maiores volumes de resíduos gerados diariamente.

🎯 Problema e objetivo

Muitas pessoas não reciclam por falta de informação: não sabem como separar cada material, onde entregar os recicláveis ou em que dia e horário o caminhão passa na sua rua.

Objetivo: reunir essas informações em um único aplicativo, simples e acessível, para tornar a reciclagem parte da rotina da população.

✨ Funcionalidades
Funcionalidade	Descrição

📘 Guia de reciclagem	Orienta como separar e descartar corretamente plástico, papel, vidro, metal, orgânicos, eletrônicos, óleo de cozinha e outros materiais.

📍 Pontos de coleta	Exibe no mapa os locais mais próximos para entrega de recicláveis, como ecopontos, cooperativas e postos de coleta seletiva.

🚛 Horários da coleta	Informa os dias e horários de passagem dos caminhões de coleta comum e seletiva, de acordo com o endereço do usuário.

🔔 Lembretes (planejado)	Notificações antes da passagem do caminhão.

🔎 Busca por material (planejado)	Pesquisa rápida para saber se um item é reciclável e como descartá-lo.

🌍 Alinhamento com os ODS

O projeto contribui com os Objetivos de Desenvolvimento Sustentável da ONU:

ODS 11 – Cidades e Comunidades Sustentáveis
ODS 12 – Consumo e Produção Responsáveis

🛠️ Tecnologias utilizadas

⚠️ Ajuste esta seção conforme as tecnologias que a equipe realmente utilizar.

Front-end / App: React Native · Flutter · HTML, CSS e JavaScript (escolha uma)
Back-end: Node.js · Python · Java (escolha uma)
Banco de dados: PostgreSQL · MySQL · Firebase (escolha uma)
Mapas e geolocalização: Google Maps API · OpenStreetMap / Leaflet
Versionamento e organização: Git, GitHub e GitHub Projects
Design: Figma

📂 Estrutura do projeto

Exemplo de estrutura. Adapte conforme o projeto evoluir.

ReciclaBem/
├── docs/              # Documentação, requisitos e protótipos

├── src/

│   ├── components/    # Componentes reutilizáveis

│   ├── screens/       # Telas do aplicativo

│   ├── services/      # Integrações com APIs e dados

│   └── assets/        # Imagens, ícones e fontes

├── data/              # Dados de pontos de coleta e horários

├── .gitignore

├── LICENSE

└── README.md

🚀 Como executar
Pré-requisitos
Git
Node.js (versão LTS) (ajuste conforme a tecnologia usada)
Um emulador ou dispositivo físico para testar o app
Passo a passo
bash
# 1. Clone o repositório
git clone https://github.com/TelinhoDragon/ReciclaBem.git

# 2. Acesse a pasta do projeto
cd ReciclaBem

# 3. Instale as dependências
npm install

# 4. Configure as variáveis de ambiente
cp .env.example .env
# edite o arquivo .env com suas chaves (ex.: chave da API de mapas)

# 5. Inicie o projeto
npm start
🗂️ Fontes de dados

Os dados de pontos de coleta e horários devem ser obtidos de fontes oficiais e abertas, como:

Portais de dados abertos da Prefeitura de São Paulo
Informações da coleta seletiva e dos ecopontos divulgadas pela prefeitura e pelas concessionárias
Cooperativas de catadores e entidades parceiras

Sempre cite a fonte e a data de atualização dos dados exibidos no aplicativo.

🗺️ Roadmap
 Definição do tema e escopo
 Levantamento de requisitos
 Protótipo das telas no Figma
 Guia de reciclagem
 Mapa com pontos de coleta
 Consulta de horários de coleta por endereço
 Notificações e lembretes
 Busca por tipo de material
 Testes com usuários
 Expansão para outras cidades do estado

🤝 Como contribuir

Contribuições são bem-vindas!

Faça um fork do projeto
Crie uma branch para sua alteração: git checkout -b feature/minha-feature
Faça o commit: git commit -m "feat: adiciona minha feature"
Envie para o seu fork: git push origin feature/minha-feature
Abra um Pull Request

👥 Equipe

Projeto desenvolvido por estudantes da Fatec Barueri.

Nome	Função	GitHub
Nome do integrante	Desenvolvedor	@TelinhoDragon


Orientação: Prof(a). VANDER RIBEIRO ELME Curso: Gestão Da Tecnologia da Informação · Semestre: 3º

📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

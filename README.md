# TORONTO LOGÍSTICA - Sistema de Gestão

Ferramenta profissional de gestão logística com rastreamento em tempo real, gestão de motoristas, clientes, rotas e viagens.

## Ço Funcionalidades

- 🔒 **Login Premium**: Tela de login com botão de entrar, logo da TORONTO LOGÍSTICA, imagem de fundo profissional e barra superior com logo
- 📊 **Painel Principal Interativo**: Dashboard amplo e expansivo mostrando: quantidade de clientes sem motorista, motoristas disponíveis/indisponíveis/em oficina com placas, viagens do dia, status em tempo real com cores indicativas e avisos sonoros
- 🚗 **Cadastro Motorista + Veículo**: Cadastro unificado de motorista e veículo (placa, modelo, etc), com funções de editar e excluir, controle automático de status (Disponível/Indisponível/Oficina)
- 👥 **Cadastro de Clientes**: Cadastro completo de clientes com editar e excluir, contador automático de clientes sem motorista que diminui quando motorista é atribuído
- 🗺️ **Cadastro de Rotas com Cálculo Automático**: Cadastro de rotas com origem e destino (formato Cidade/UF), cálculo automático de distância usando dados do OpenStreetMap, editar e excluir
- 📦 **Programação de Viagens**: Sistema de programação com motorista opcional, campos: Pedido/Fatura OS, Cliente, Rota, Data/Hora Programação (autopreenchida com data/hora atual), funções editar, excluir e cancelar
- 🔍 #�cFiltro Inteligente por Data**: Filtro que mostra automaticamente apenas viagens programadas do dia atual, atualiza automaticamente à meia-noite (00h), com opção de filtrar viagens anteriores e posteriores
-���� **Controle de Status da Viagem**: Status automáticos: Programada (sem motorista) : Em Andamento (motorista atribuído) → Trânsito (após chegada no cliente) → No Local (ao chegar no cliente) → Em Trân&�to (após saída) → Entregue (ao completar agendamento TECON)
- ⊱ ��**Cronɴmetro Tempo de Chegada automático**: Data/Hora Programção que inicia ao inserir Data/Hora Chegada Cliente, mostrando tempo real mostrando status de EM ANDAMENTO até o tempo zera e troca status para 'No Local' 
- ⊱ ��**Cronɴmetro Tempo de Entrega**: Cronômetro automático quando for preenchida Data/Hora Saída Cliente e conta até o prazo Data/Hora Agendamento TECON, mostrando EM TRÂNSITO E tempo restante em tempo real, muda status para 'Entregue' ao completar
- 🛡 ‍♀️ **Gestão de Status do Motorista**: Controle automático: motorista fica indisponível ao ser atribuído a viagem, volta para disponível quando viagem é finalizada, opção manual para status Oficina
- 🔧 **Gestão de Oficina**: Módulo para registrar veículos em manutenção, com data entrada/saída, descrição do serviço, editar, excluir e cancelar
- 🌍 **Mapa Interativo em Tempo Real**: Mapa do Brasil mostrando rotas calculadas automaticamente entre cidades (formato Cidade/UF), ícones de caminzões em movimento, rastreamento GPS em tempo real via número de telefone do motorista, atualização conforme cron�metros
- 📱 🚨 **Notificação WhatsApp Automática**: Envio automático de mensagem WhatsApp para o motorista quando ele for atribuído a uma viagem, incluindo detalhes da rota, cliente e horários
- ⚠️ **Alertas Visuais e Sonoros**: Sistema de cores indicativas para cada status (verde=disponível, vermelho=indisponível, amarelo=trân˩to, azul=no local, etc) com avisos sonoros ao trocar de status
- 🔢 **Contador de Clientes Sem Motorista**: Exibição em destaque no painel da quantidade de clientes aguardando motorista, diminui automaticamente quando motorista é atribuído

## 🎚**Styles**

-🎨 **Cor Principal**: #1e3a8a
-🎨 **Cor Secundária**: #3b82f6
-🎨 **Layout Premium**: Design amplo e expansivo com cards grandes, espaçamento generoso, sombras suaves, bordas arredondadas, gradientes sutis, animações de transição suaves
-🎨 **Tipografia Profissional**: Fontes modernas sans-serif, títulos em negrito, hierarquia clara, tamanhos grandes para leitura fácil
-🎨 **Imagens e Logo**: TORONTO LOGÍSTICA na barra superior e tela de login, imagem de fundo profissional (caminhões,"estrada) na tela de login, ícones realistas de caminhões no mapa
-🎨 **Cores de Status**: Verde (#4caf50) = Disponível, Vermelho (#f44336) = Indisponível, Amarelo (#ffc107) = Trânsito, Azul (#2196f3) = No Local, Roxo (#9c27b0) = Entregue, Cinza (#757575) = Oficina
- 🎨 **Interatividade**: Hover efeitos em cards e botões, animações de Leading nos cronɴmetros, transições suaves entre telas, feedback visual imediato em todas ações
-🎨 **Responsividade**: Design adaptável para desktop (painel amplo), tablet e mobile, mapa interativo responsivo

## 🚂 Tecnologias

- HTML5
- CSS3 com variáveis CSS
- JavaScript Vanilla
- LocalStorage para persistência de dados
- Google Maps API (para cálculo de distâncias)
- WhatsApp Business API (para notificações)
- Responsive Design

Projeto criado com Composio.

## П️ Como Usar

1. Abra o arquivo `index.html` no seu navegador
2. Faça login com qualquer usuário e senha
3. Começe a cadastrar motoristas, clientes, rotas e viagens
4. Acompanhe o status das viagens em tempo real


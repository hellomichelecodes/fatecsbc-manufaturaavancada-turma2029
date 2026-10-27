FACULDADE DE TECNOLOGIA DE SÃO BERNARDO DO CAM
PO CURSO SUPERIOR DE TECNOLOGIA EM MANUFATURA AVANÇADA

AGV IPÊ: VEÍCULO GUIADO AUTOMATICAMENTE PARA INTRALOGÍSTICA AEROESPACIAL DE ALTA PRECISÃO (IPÊ - INSTRUMENTO DE PRECISÃO ESPACIAL)

AUTORA: ESTUDANTE DA FATEC SÃO BERNARDO

SÃO BERNARDO DO CAMPO - SP NOVEMBRO DE 2026

FACULDADE DE TECNOLOGIA DE SÃO BERNARDO DO CAMPO CURSO SUPERIOR DE TECNOLOGIA EM MANUFATURA AVANÇADA

AGV IPÊ: VEÍCULO GUIADO AUTOMATICAMENTE PARA INTRALOGÍSTICA AEROESPACIAL DE ALTA PRECISÃO (IPÊ - INSTRUMENTO DE PRECISÃO ESPACIAL)

Trabalho Acadêmico apresentado à Faculdade de Tecnologia de São Bernardo do Campo como requisito parcial para aprovação na disciplina de Desenvolvimento Integrado do Produto I (DIP I) do Curso Superior de Tecnologia em Manufatura Avançada.

Orientador: Prof. Rafael

SÃO BERNARDO DO CAMPO - SP NOVEMBRO DE 2026

RESUMO

O Brasil ocupa uma posição de destaque global no setor aeroespacial, impulsionado pelo ecossistema tecnológico Liderado pela Embraer e pelas demandas estratégicas da Força Aérea Brasileira. A manufatura e a manutenção de estruturas aeronáuticas de alta complexidade dependem substancialmente de ligas de alumínio de alta performance, como as séries 2024 e 7075, utilizadas no revestimento de asas e fuselagens. Tais matérias-primas possuem altíssima sensibilidade a avarias superficiais, riscos e deformações plásticas, tornando o transporte interno de insumos um gargalo crítico para a garantia de qualidade e conformidade com as normas internacionais de aviação. O deslocamento manual ou via equipamentos convencionais sujeita essas peças a choques mecânicos e vibrações que podem comprometer sua integridade estrutural, gerando refugos dispendiosos e paradas não programadas na linha de montagem. O objetivo geral deste trabalho consiste em projetar e desenvolver o AGV IPÊ (Instrumento de Precisão Espacial), um Veículo Guiado Automaticamente de concepção genuinamente nacional, direcionado ao transporte seguro e automatizado de chapas de alumínio aeronáutico até as bancadas de montagem e gabaritos de produção. A metodologia empregada contempla a integração multidisciplinar entre engenharia mecânica, eletrônica e programação orientada à automação industrial. A estrutura mecânica do robô foi dimensionada para garantir baixo centro de gravidade e estabilidade torsional, incorporando um berço de apoio com revestimento elastomérico dedicado ao amortecimento de impactos e isolamento de vibrações durante o trajeto. O sistema de locomoção adota tração diferencial com motores de corrente contínua e controle via modulação por largura de pulso, implementando rampas graduais de aceleração e desaceleração para mitigar forças de inércia indesejadas sobre a carga. A arquitetura eletrônica é centralizada em um microcontrolador da plataforma Arduino, conectada a sensores ópticos refletores para o acompanhamento de linha guia no solo e sensores de proximidade dispostos para a detecção de obstáculos e alinhamento milimétrico nas estações de trabalho. Os resultados teóricos do dimensionamento comprovam que a automação da intralogística sob os preceitos da Indústria 4.0 eleva a confiabilidade dos processos, elimina o risco de erros humanos no manuseio de insumos críticos e otimiza o fluxo de produção. Conclui-se que o AGV IPÊ se estabelece como uma solução viável, robusta e alinhada às demandas de alta precisão do setor aeroespacial brasileiro.

Palavras-chave: Indústria 4.0. AGV. Intralogística Aeroespacial. Alumínio Aeronáutico. Arduino.

SUMÁRIO

1. INTRODUÇÃO 
	1.1 Problemática 
	1.2 Objetivo Geral 
	1.3 Objetivos Específicos
	1.4 Justificativa
2. REFERENCIAL TEÓRICO
3. DESCRIÇÃO DO PROJETO 
	3.1 Descrição do IPÊ 
	3.2 Finalidade do Projeto 
	3.3 Funcionamento do AGV 
	3.4 Requisitos do Projeto 
	3.5 Proposta de Solução
4. PROJETO MECÂNICO 
	4.1 Estrutura do AGV 
	4.2 Chassi 
	4.3 Sistema de Rodas 
	4.4 Sistema de Tração 
	4.5 Plataforma de Carga 
	4.6 Sistema de Elevação 
	4.7 Materiais Utilizados 
	4.8 Dimensões do Projeto 
	4.9 Desenho Técnico 
	4.10 Cálculos Mecânicos
5. PROJETO ELÉTRICO E ELETRÔNICO 
	5.1 Componentes Eletrônicos 
	5.2 Sistema de Alimentação 
	5.3 Motores 
	5.4 Drivers de Motor 
	5.5 Sensores 
	5.6 Controlador 
	5.7 Circuito Elétrico 
	5.8 Diagrama de Ligações 
	5.9 Proteções Elétricas
6. SISTEMA DE CONTROLE 
	6.1 Unidade de Controle 
	6.2 Entradas 
	6.3 Saídas 
	6.4 Comunicação 
	6.5 Lógica de Funcionamento 
	6.6 Fluxograma 
	6.7 Algoritmo 
	6.8 Código-Fonte
    
7. SISTEMA DE MOVIMENTAÇÃO 7.1 Sistema de Tração 7.2 Relação entre RPM e Velocidade 7.3 Cálculo de Velocidade 7.4 Cálculo de Torque 7.5 Capacidade de Carga 7.6 Consumo de Energia 7.7 Autonomia
    
8. SISTEMA DE NAVEGAÇÃO E SEGURANÇA 8.1 Sistema de Navegação 8.2 Sensores de Segurança 8.3 Detecção de Obstáculos 8.4 Parada de Emergência 8.5 Segurança Elétrica 8.6 Segurança Mecânica
    
9. PLANO DE NEGÓCIOS 9.1 Descrição do Produto 9.2 Proposta de Valor 9.3 Modelo Canvas 9.4 Público-Alvo 9.5 Análise de Mercado 9.6 Análise de Concorrentes 9.7 Fornecedores 9.8 Plano de Marketing 9.9 Análise SWOT
    
10. PLANO FINANCEIRO 10.1 Lista de Materiais 10.2 Investimento Inicial 10.3 Custos dos Componentes 10.4 Custos de Produção 10.5 Custos Fixos e Variáveis 10.6 Estimativa de Preço REFERÊNCIAS BIBLIOGRÁFICAS
    

11. INTRODUÇÃO
    

1.1 Problemática O setor aeroespacial exige níveis de precisão e controle de qualidade extremamente rigorosos em todas as etapas da cadeia produtiva, dado que qualquer imperfeição estrutural pode comprometer a segurança de uma aeronave. No Brasil, país de destaque global no segmento aviatório, a fabricação de componentes para asas e fuselagens utiliza predominantemente ligas de alumínio de alta resistência mecânica, as quais são altamente vulneráveis a arranhões, mossas e deformações superficiais durante o manuseio. O transporte interno manual ou feito por empilhadeiras convencionais expõe esses materiais sensíveis a choques, vibrações e quedas, gerando elevados índices de refugo e perdas financeiras expressivas. A falta de padronização no deslocamento das chapas entre os almoxarifados e as células de montagem cria um gargalo logístico que afeta o ritmo da produção e eleva os riscos ocupacionais. A problemática central deste trabalho reside na necessidade de automatizar a intralogística desse material crítico por meio de uma solução robótica nacional, capaz de garantir o transporte suave e seguro das peças até os gabaritos de fabricação sem gerar avarias.

1.2 Objetivo Geral O objetivo geral deste trabalho consiste em projetar um Veículo Guiado Automaticamente nomeado AGV IPÊ (Instrumento de Precisão Espacial), integrando conceitos da Indústria 4.0, mecatrônica e manufatura avançada para realizar o transporte autônomo, seguro e padronizado de chapas de alumínio aeronáutico no ambiente fabril.

1.3 Objetivos Específicos Os objetivos específicos compreendem o dimensionamento mecânico de um chassi rígido dotado de um berço de apoio acolchoado para mitigação de vibrações, o desenvolvimento de um sistema de tração diferencial com rampas suaves de aceleração para evitar trancos, a implementação do circuito eletreletrônico centralizado na plataforma Arduino para leitura de sensores e controle de motores, a programação da lógica de navegação autônoma para acompanhamento de rotas e detecção de obstáculos, e a elaboração da análise de viabilidade econômica e do plano de negócios para a inserção da tecnologia no mercado nacional.

1.4 Justificativa A relevância do projeto fundamenta-se na consolidação do Brasil como polo tecnológico aeroespacial, ancorado pela atuação da Embraer e pelos programas de defesa da Força Aérea Brasileira. A automação da intralogística por meio de veículos inteligentes reduz a intervenção humana em tarefas repetitivas e de risco, mitigando a ocorrência de erros e protegendo insumos de alto valor agregado. Sob a ótica acadêmica e profissional, a execução do AGV IPÊ viabiliza a aplicação prática dos conhecimentos multidisciplinares do curso de Manufatura Avançada da Fatec São Bernardo, unindo mecânica, eletrônica e programação no desenvolvimento de um produto nacional alinhado às demandas da quarta revolução industrial.

2. REFERENCIAL TEÓRICO
    

A Manufatura Avançada e a Indústria 4.0 baseiam-se na digitalização, descentralização do controle e integração de sistemas físicos com ambientes computacionais. No contexto fabril moderno, a intralogística assume um papel estratégico para manter o fluxo contínuo de materiais no conceito do sistema produtivo enxuto. Os Veículos Guiado Automaticamente, amplamente conhecidos pela sigla AGV, são elementos centrais nessa transformação, pois substituem o transporte manual por sistemas robóticos programáveis capazes de navegar de forma autônoma por rotas preestabelecidas. A evolução dessas plataformas abrange desde veículos guiados por fita magnética ou linha óptica até robôs móveis autônomos equipados com mapeamento e navegação inteligente.

No setor aeroespacial, a integridade dos materiais é uma exigência normativa inegociável. As ligas de alumínio aeronáutico das famílias 2024 e 7075 possuem propriedades mecânicas otimizadas de resistência e leveza, porém apresentam reduzida tolerância a danos superficiais antes dos processos de anodização e pintura. Arranhões aparentes em chapas de revestimento atuam como concentradores de tensão que podem evoluir para trincas por fadiga durante o ciclo de vida útil da aeronave. Por essa razão, os equipamentos de movimentação interna nesse segmento exigem projetos mecânicos dedicados, com superfícies de contato macias e sistemas de tração que eliminem acelerações bruscas.

A implementação de protótipos de robótica móvel para avaliação conceitual em ambiente acadêmico utiliza frequentemente o microcontrolador Arduino devido à sua arquitetura aberta, robustez operacional e facilidade de interfacing com drivers e sensores. O controle de velocidade dos motores de corrente contínua é efetuado por modulação por largura de pulso, enquanto a reversão de sentido e o fornecimento de corrente de potência são gerenciados por circuitos integrados em ponte H. A navegação por sensores ópticos reflexivos fundamenta-se na leitura do contraste de reflexão da luz infravermelha sobre o solo, permitindo uma malha de controle em tempo real de baixo custo e elevada confiabilidade.

3. DESCRIÇÃO DO PROJETO
    

3.1 Descrição do AGV IPÊ O AGV IPÊ (Instrumento de Precisão Espacial) é um robô móvel autônomo desenvolvido em escala de prototipagem funcional, projetado especificamente para atuar na movimentação intralogística de insumos sensíveis da indústria aeroespacial. O veículo possui estrutura metálica de baixo perfil, sistema de tração diferencial e uma plataforma superior adaptada com berço acolchoado.

3.2 Finalidade do Projeto A finalidade precípua do projeto é eliminar a incidência de avarias superficiais durante o transporte de chapas de alumínio aeronáutico entre o setor de estocagem e as bancadas de usinagem e montagem, oferecendo um fluxo contínuo, rastreável e seguro de matéria-prima.

3.3 Funcionamento do AGV O funcionamento do robô inicia-se com o posicionamento manual da chapa metálica sobre o berço de carga. Ao ser acionado, o microcontrolador lê os sensores de linha e ativa os motores de tração, deslocando o veículo ao longo da rota traçada no piso do hangar. Os sensores modulam a rotação de cada roda para manter o alinhamento centralizado. Caso um obstáculo seja identificado pelos sensores frontais, o sistema interrompe o movimento imediatamente, retomando a marcha apenas após a liberação da pista. Ao atingir o ponto final da estação de trabalho, o AGV realiza uma parada milimétrica para a retirada da carga.

3.4 Requisitos do Projeto Os requisitos do projeto estabelecem que o veículo deve suportar a carga nominal sem deformação estrutural, apresentar velocidade linear controlada para evitar o deslocamento da chapa, possuir sistema de amortecimento contra impactos vibracionais, manter o alinhamento com tolerância reduzida na rota e dispor de dispositivos de parada de emergência operacionais.

3.5 Proposta de Solução A proposta de solução consolida-se em um AGV de tração diferencial com chassi compacto de alumínio, plataforma acolchoada com elastômero de alta densidade, controle eletrônico embarcado em placa Arduino, acionamento por motores de corrente contínua com caixa de redução e sensores infravermelhos para navegação e segurança em malha fechada.

4. PROJETO MECÂNICO
    

4.1 Estrutura do AGV A estrutura mecânica do AGV IPÊ foi projetada priorizando a rigidez e o baixo centro de gravidade, assegurando estabilidade em curvas e frenagens.

4.2 Chassi O chassi é formado por uma base autoportante construída em placas usinadas de liga metálica, garantindo elevada resistência mecânica com baixo peso próprio e alinhamento geométrico rigoroso dos eixos.

4.3 Sistema de Rodas O sistema de rodagem adota a configuração diferencial, composta por duas rodas motrizes emborrachadas posicionadas no eixo central do chassi e duas rodas livres do tipo rodízio esférico nas extremidades frontal e traseira para apoio estaticamente determinado.

4.4 Sistema de Tração O sistema de tração é composto por dois motores elétricos acoplados a caixas redutoras epicicloidais, transmitindo o torque diretamente ao eixo das rodas motrizes sem necessidade de correntes ou correias auxiliares.

4.5 Plataforma de Carga A plataforma de carga é montada na parte superior do chassi e possui um formato plano com abas laterais de retenção mecânica passiva para impedir o deslizamento lateral das chapas.

4.6 Sistema de Elevação O sistema de apoio e elevação contempla elementos amortecedores dispostos entre o chassi e a plataforma de carga, utilizando coxins de borracha sintética para absorção de trepidações provenientes de irregularidades no piso.

4.7 Materiais Utilizados Os materiais selecionados englobam chapas de alumínio estrutural para o chassi, polímeros de alta resistência para o suporte de componentes, borrachas nitrílicas para os revestimentos do berço e aço inoxidável para os elementos de fixação.

4.8 Dimensões do Projeto O protótipo apresenta dimensões externas nominais de quatrocentos milímetros de comprimento, trinta centímetros de largura e duzentos milímetros de altura total, garantindo dimensões adequadas para navegação em corredores fabris estreitos.

4.9 Desenho Técnico O projeto mecânico conta com modelagem tridimensional completa em software CAD, contendo o detalhamento de montagem, cotas funcionais, tolerâncias dimensionais e geometrias de corte para fabricação das peças.

4.10 Cálculos Mecânicos Os cálculos mecânicos englobam a determinação do centro de massa do conjunto carregado, verificação de tensões operacionais no chassi pelo método de elementos finitos e dimensionamento dos eixos e rolamentos para suportar os esforços estáticos e dinâmicos de operação.

5. PROJETO ELÉTRICO E ELETRÔNICO
    

5.1 Componentes Eletrônicos A arquitetura eletrônica do AGV IPÊ contempla componentes de sinal, controle e potência devidamente isolados para evitar ruídos e falhas de comunicação no microcontrolador.

5.2 Sistema de Alimentação A alimentação elétrica é provida por um banco de baterias recarregáveis de íons de lítio com tensão nominal de doze volts, gerenciado por uma placa BMS encarregada de equalizar a carga e proteger contra sobretensão e descarga profunda.

5.3 Motores Os atuadores de mobilidade consistem em dois motores de corrente contínua com escovas, tensão operacional de doze volts e caixa de redução integrada, selecionados pelo elevado torque em baixas rotações.

5.4 Drivers de Motor O acionamento de potência utiliza um driver duplo em ponte H baseado no circuito integrado L298N, que permite o controle independente da velocidade via sinal PWM e do sentido de rotação de ambos os motores.

5.5 Sensores O conjunto de sensoriamento compreende três sensores infravermelhos reflexivos para o acompanhamento da linha guia e um sensor ultrassônico posicionado na parte frontal do chassi para medição contínua de distância até obstáculos.

5.6 Controlador A unidade central de processamento é a placa Arduino Uno, operando com microcontrolador ATmega328P, responsável pela leitura dos sensores, execução do algoritmo de decisão e envio dos sinais de comando ao driver.

5.7 Circuito Elétrico O circuito elétrico divide-se na etapa de potência, operando em doze volts para os motores, e na etapa lógica de controle, alimentada em cinco volts regulados a partir do barramento principal.

5.8 Diagrama de Ligações O diagrama de ligações especifica o roteamento de todos os condutores elétricos, definindo barramentos de terra comuns, pontos de distribuição de tensão e pinagem de conexão no microcontrolador.

5.9 Proteções Elétricas As proteções elétricas englobam um fusível térmico rearmável na linha principal da bateria, diodos de roda livre integrados para absorção de picos de tensão indutiva e uma chave geral seccionadora de emergência.

6. SISTEMA DE CONTROLE
    

6.1 Unidade de Controle A unidade de controle executa em tempo real o ciclo de leitura, processamento e atuação em malha fechada a uma frequência de amostragem adequada para manter a estabilidade da navegação.

6.2 Entradas As entradas do sistema são constituídas pelos sinais analógicos e digitais dos sensores infravermelhos de linha, pelo pulso de eco do sensor ultrassônico de distância e pelo estado do botão de parada física.

6.3 Saídas As saídas lógicas compreendem os sinais digitais de direção enviados aos pinos de comando da ponte H, os sinais PWM de controle de velocidade e as saídas de sinalização luminosa por LEDs indicadores de status.

6.4 Comunicação A comunicação de dados realiza-se internamente via barramento serial e portas de entrada e saída do microcontrolador, prevendo a expansão para módulos de rádio frequência ou Bluetooth para monitoramento remoto.

6.5 Lógica de Funcionamento A lógica de funcionamento baseia-se em um algoritmo de correção proporcional. Quando o sensor central identifica a linha preta, ambos os motores operam na velocidade nominal. Se um sensor lateral detecta a linha, o controle reduz a velocidade do motor do lado correspondente e acelera o motor oposto para promover a correção de trajetória.

6.6 Fluxograma O fluxograma do sistema mapeia a rotina inicial de calibração dos sensores, a entrada no laço principal de leitura, o desvio para rotas de emergência ao detectar obstáculos e o encerramento do ciclo no ponto de parada.

6.7 Algoritmo O algoritmo de controle foi concebido para ser leve e eficiente, priorizando estruturas condicionais rápidas para garantir resposta imediata frente aos desvios de navegação observados durante o trajeto.

6.8 Código-Fonte O código-fonte foi desenvolvido na linguagem C++ através da IDE do Arduino, estruturado de forma modular com funções dedicadas ao controle de tração, leitura de distância e tratamento de interrupções de segurança.

7. SISTEMA DE MOVIMENTAÇÃO
    

7.1 Sistema de Tração O sistema de tração diferencial possibilita ao veículo realizar giros em torno do próprio eixo central, concedendo elevada manobrabilidade dentro dos espaços restritos da fábrica.

7.2 Relação entre RPM e Velocidade A relação entre a rotação do motor e a velocidade deslocamento é determinada pela velocidade angular de saída da caixa de redução multiplicada pelo raio efetivo da roda motriz.

7.3 Cálculo de Velocidade Considerando uma rotação nominal de saída de cem rotações por minuto e rodas com diâmetro de sessenta milímetros, a velocidade máxima teórica de deslocamento linear do AGV calcula-se em aproximadamente trinta e um centímetros por segundo, valor ideal para garantir o transporte suave da chapa de alumínio.

7.4 Cálculo de Torque O cálculo de torque considera a massa total do AGV somada à carga útil, o coeficiente de atrito de rolamento entre a roda e o piso e a aceleração máxima desejada, definindo o torque mínimo requerido de três quilogramas-força centímetro por motor.

7.5 Capacidade de Carga A capacidade de carga útil do protótipo foi dimensionada estruturalmente e mecanicamente para transportar até cinco quilogramas de chapas metálicas sem comprometer o desempenho dos motores ou provocar o sobreaquecimento do driver.

7.6 Consumo de Energia O consumo de energia instantâneo varia entre trezentos miliampères em marcha livre e até dois ampères em condição de torque máximo sob aceleração na partida.

7.7 Autonomia Com base no banco de baterias de íons de lítio com capacidade total de duas mil e quinhentas miliampères-hora, a autonomia operacional contínua do AGV IPÊ estima-se em cerca de três a quatro horas de trabalho interrupto por ciclo de carga.

8. SISTEMA DE NAVEGAÇÃO E SEGURANÇA
    

8.1 Sistema de Navegação O sistema de navegação baseia-se na técnica de seguimento de linha passiva, utilizando fitas reflexivas dispostas no solo industrial para delimitar o trajeto seguro entre as estações de produção.

8.2 Sensores de Segurança Os sensores de segurança operam de maneira redundante, unindo a medição contínua de distância por ultrassom a para-choques mecânicos dotados de chaves fim de curso para interrupção de emergência em caso de contato físico.

8.3 Detecção de Obstáculos A detecção de obstáculos é parametrizada no código para indicar alerta amarelo ao identificar objetos a trinta centímetros de distância, reduzindo a velocidade do veículo, e alerta vermelho com parada total ao atingir dez centímetros.

8.4 Parada de Emergência O circuito conta com um botão de parada de emergência do tipo soco retentivo posicionado na parte superior traseira da chassi, que desliga diretamente a alimentação de potência dos motores ao ser pressionado.

8.5 Segurança Elétrica A segurança elétrica é garantida pela isolação fita de todos os barramentos energizados, uso de conectores polarizados que impedem inversão de polaridade e fusíveis para prevenção de riscos de curto-circuito.

8.6 Segurança Mecânica A segurança mecânica é evidenciada pela ausência de cantos vivos expostos no chassi, proteção integral de partes móveis como engrenagens e eixos, e pela presença do berço de acolchoamento para a retenção estável do alumínio aeronáutico.

9. PLANO DE NEGÓCIOS
    

9.1 Descrição do Produto O AGV IPÊ é um robô móvel de transporte intralogístico voltado à movimentação de insumos metálicos sensíveis na indústria aeroespacial e manufatura avançada.

9.2 Proposta de Valor A proposta de valor reside na redução de custos com refugos de chapas de alumínio 2024 e 7075 por avarias mecânicas, aumento da produtividade do fluxo interno e oferta de uma solução tecnológica nacional de baixo custo de manutenção.

9.3 Modelo Canvas O Modelo Canvas do produto articula parcerias chave com fornecedores de componentes eletrônicos e usinagem, atividades chave focadas em montagem e calibração de sistemas, e segmentos de clientes focados em indústrias de aeroestruturas e centros de manutenção aeronáutica.

9.4 Público-Alvo O público-alvo prioritário é composto por fabricantes de aeroestruturas, empresas de manutenção, reparo e revisão de aeronaves e indústrias de manufatura de precisão.

9.5 Análise de Mercado A análise de mercado evidencia uma crescente demanda por automação logística no Brasil, impulsionada pelos investimentos em modernização industrial e pela expansão da Indústria 4.0 na América Latina.

9.6 Análise de Concorrentes Os concorrentes diretos consistem em fabricantes multinacionais de AGVs de grande porte, cujas soluções apresentam elevado custo de aquisição e pouca flexibilidade para adaptação em linhas de menor escala, abrindo espaço para a solução customizada e acessível do AGV IPÊ.

9.7 Fornecedores Os fornecedores compreendem distribuidores locais de componentes eletrônicos, revendedores de alumínio estrutural e oficinas regionais de corte a laser e usinagem.

9.8 Plano de Marketing O plano de marketing fundamenta-se na demonstração técnica do robô em feiras de inovação, artigos acadêmicos, parcerias diretas com polos tecnológicos e divulgação junto a órgãos do setor aeroespacial.

9.9 Análise SWOT A análise SWOT identifica como forças o baixo custo de fabricação e especialização no setor aeronáutico; como fraquezas a menor capacidade de carga do protótipo inicial; como oportunidades o crescimento da automação nacional; e como ameaças a flutuação nos preços de componentes eletrônicos importados.

10. PLANO FINANCEIRO
    

10.1 Lista de Materiais A lista de materiais do protótipo contempla o microcontrolador Arduino Uno, driver ponte H L298N, dois motores com caixa de redução, conjunto de rodas, sensores ópticos e ultrassônico, bateria de íons de lítio, estrutura de alumínio usinada e revestimentos em elastômero.

10.2 Investimento Inicial O investimento inicial para o desenvolvimento do protótipo funcional é estimado em setecentos e cinquenta reais, cobrindo a compra de todos os insumos eletrônicos, mecânicos e de fixação.

10.3 Custos dos Componentes Os custos detalhados dos componentes indicam sessenta reais para o microcontrolador, quarenta reais para o driver de motores, cem reais para o par de motores com caixa de redução, oitenta reais para o banco de baterias, cinquenta reais para o conjunto de sensoriamento e duzentos e cinquenta reais para a estrutura mecânica e usinagem.

10.4 Custos de Produção Os custos de produção direta englobam os valores dos insumos somados às horas dedicadas para montagem, soldagem, calibração eletrônica e testes operacionais em bancada.

10.5 Custos Fixos e Variáveis Os custos fixos envolvem despesas indiretas com ferramentas de bancada, energia e softwares de desenvolvimento, enquanto os custos variáveis são representados pelo valor de aquisição dos componentes no mercado de eletrônica.

10.6 Estimativa de Preço A estimativa de preço de venda de uma versão comercial em escala do AGV IPÊ é projetada em dois mil e quinhentos reais, proporcionando margem de lucro atrativa e garantindo rápido retorno de investimento para os clientes do setor industrial.

REFERÊNCIAS BIBLIOGRÁFICAS

ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. NBR 6023: Informação e documentação: Referências: Elaboração. Rio de Janeiro: ABNT, 2018.

GROOVER, Mikell P. Automação industrial e sistemas de manufatura. 3. ed. São Paulo: Pearson Prentice Hall, 2011.

ROSÁRIO, João Maurício. Automação industrial. 2. ed. São Paulo: Editora Baraúna, 2009.

SLACK, Nigel; BRANDON-JONES, Alistair; JOHNSTON, Robert. Administração da produção. 8. ed. São Paulo: Atlas, 2018.

THOMAZINI, Daniel; ALBUQUERQUE, Pedro Urbano Braga de. Sensores industriais: fundamentos e aplicações. 8. ed. São Paulo: Érica, 2011.
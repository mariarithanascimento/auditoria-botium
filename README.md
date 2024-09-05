# Conduzindo uma auditoria de segurança: Botium Toys

> Olá!! Bem vindo ao estudo de caso "Conduzindo uma auditoria de segurança: Botium Toys". Nele você encontrará uma breve explicação das Categorias de Controle, o escopo da empresa e por fim o checklist. 

## Summary
- [Categorias de Controle](#Categorias-de-Controle)
- [Botium Toys: Relatório de Escopo, Objetivos e Avaliação de Riscos](#BotiumToys-RelatórioDeEscopo-Objetivos-e-AvaliaçãoDeRiscos)
- [Checklist - Controle de segurança (pdf)]()


## `Categorias de Controle`

Os controles dentro da cibersegurança são agrupados em três categorias principais: 

 - Controles Administrativos/Gerenciais  
 - Controles Técnicos  
 - Controles Físicos/Operacionais

**Controles Administrativos/Gerenciais** abordam o componente humano da cibersegurança. Esses controles incluem políticas e procedimentos que definem como uma organização gerencia dados e esclarecem as responsabilidades dos funcionários, incluindo seu papel na proteção da organização. Embora os controles administrativos geralmente sejam baseados em políticas, a aplicação dessas políticas pode exigir o uso de controles técnicos ou físicos. 
**Controles Técnicos** consistem em soluções como firewalls, sistemas de detecção de intrusão (IDS), sistemas de prevenção de intrusão (IPS), produtos antivírus (AV), criptografia, etc. Os controles técnicos podem ser usados de várias maneiras para atender aos objetivos organizacionais. 
**Controles Físicos/Operacionais** incluem fechaduras de portas, fechaduras de armários, câmeras de vigilância, leitores de crachá, etc. Eles são usados para limitar o acesso físico a ativos físicos por pessoal não autorizado. 

### Tipos de controle
Os tipos de controle incluem, mas não se limitam a: 

 - Preventivo 
 - Corretivo
 - Detectivo 
 - Dissuasivo

Esses controles trabalham em conjunto para fornecer uma defesa em profundidade e proteger ativos. Os *controles preventivos* são projetados para evitar que um incidente ocorra. *Controles corretivos* são usados para restaurar um ativo após um incidente. *Controles detetivos* são implementados para determinar se um incidente ocorreu ou está em andamento. *Controles dissuasivos* são projetados para desencorajar ataques.

### Controles Administrativos/Gerenciais
|Nome do Controle| Tipo de Controle |Finalidade do Controle |
|------------------------------------|--|--|
|Princípio do Menor Privilégio | Preventivo | Reduzir o risco e o impacto geral de insiders maliciosos ou contas comprometidas                                 
|Planos de recuperação de desastres | Corretivo | Proporcionar continuidade dos negócios 
|Políticas de senhas | Preventivo | Reduzir a probabilidade de comprometimento de contas por técnicas de ataque de força bruta ou dicionário 
|Políticas de controle de acesso | Preventivo | Fortalecer a confidencialidade e a integridade definindo quais grupos podem acessar ou modificar dados. 
|Políticas de gerenciamento de contas | Preventivo | Gerenciar o ciclo de vida das contas, reduzindo a superfície de ataque e limitando o impacto geral de ex-funcionários descontentes e do uso de contas padrão 
|Separação de funções|Preventivo| Reduzir o risco e o impacto geral de insiders maliciosos ou contas comprometidas.

### Controles Técnicos

|Nome do Controle | Tipo de Controle |Finalidade do Controle
|--------------------------------------------------------|--|--|
| Firewall | Preventivo | Filtrar tráfego indesejado ou malicioso de entrar na rede.
IDS/IPS | Detectivo | Detectar e prevenir tráfego anômalo que corresponda a uma assinatura ou regra 
Criptografia | Dissuasivo | Proporcionar confidencialidade a informações sensíveis.
Backups | Corretivo | Restaurar/recuperar de um evento. 
Gerenciamento de senhas | Preventivo | Reduzir a fadiga de senhas. 
Software antivírus (AV) | Preventivo | Examinar para detectar e colocar em quarentena ameaças conhecidas 
Monitoramento, manutenção e intervenção manual | Preventivo | Necessário para identificar e gerenciar ameaças, riscos ou vulnerabilidades em sistemas desatualizados.

### Controles Físicos/Operacionais
| Nome do Controle  |  Tipo de Controle | Finalidade do Controle
|--|--|--|
|Cofre com controle de tempo | Dissuasivo | Reduzir a superfície de ataque e o impacto geral de ameaças físicas.
Iluminação adequada | Dissuasivo | Dissuadir ameaças limitando locais de "esconderijo". 
Circuito fechado de televisão (CCTV) | Preventivo/Detectivo | O circuito fechado de televisão é tanto um controle preventivo quanto detectivo, pois sua presença pode reduzir o risco de certos tipos de eventos ocorrerem e pode ser usado após um evento para informar sobre as condições do evento. Armários com tranca (para equipamentos de rede) | Preventivo | Fortalecer a integridade, impedindo que pessoal não autorizado e outras pessoas acessem fisicamente ou modifiquem equipamentos de infraestrutura de rede Sinalização indicando o provedor do serviço de alarme | Dissuasivo | Dissuadir certos tipos de ameaças ao tornar a probabilidade de um ataque bem-sucedido parecer baixa. 
Trancas | Dissuasivo/Preventivo | Fortalecer a integridade dissuadindo e impedindo que pessoal não autorizado acesse fisicamente os ativos.
Detecção e prevenção de incêndios (alarme de incêndio, sistema de sprinklers, etc.) | Detectivo/Preventivo | Detectar incêndio no local físico e prevenir danos a ativos físicos, como inventário, servidores, etc.

## `Botium Toys: Relatório de Escopo, Objetivos e Avaliação de Riscos`

**1. Escopo e objetivos da auditoria.** 
**Escopo:** O escopo desta auditoria abrange todo o programa de segurança da Botium Toys. Isso inclui seus ativos, como equipamentos e dispositivos dos funcionários, a rede interna e os sistemas. Será necessário revisar os ativos da Botium Toys e os controles e práticas de conformidade que estão em vigor. 
**Objetivos:** Avaliar os ativos existentes e completar a lista de verificação de controles e conformidade para determinar quais controles e melhores práticas de conformidade precisam ser implementados para melhorar a postura de segurança da Botium Toys.

**2. Ativos atuais** 
Os ativos gerenciados pelo Departamento de TI incluem: 

 - Equipamentos no local para as necessidades empresariais do
   escritório. 
  - Equipamentos dos funcionários: dispositivos de usuário
   final (desktops/laptops, smartphones), estações de trabalho remotas,
   headsets, cabos, teclados, mouses, estações de acoplamento, câmeras
   de vigilância, etc.  
   -  Produtos disponíveis para venda no varejo no
   local e online; armazenados no depósito adjacente da empresa  
   - Gestão de sistemas, software e serviços: contabilidade,
   telecomunicações, banco de dados, segurança, comércio eletrônico e
   gestão de inventário 
   - Acesso à internet 
   - Rede interna 
   - Retenção e armazenamento de dados 
   - Manutenção de sistemas legados: sistemas em fim de vida que requerem monitoramento humano.

**3. Avaliação de riscos** 
**Descrição do risco** 
Atualmente, há uma gestão inadequada dos ativos. Além disso, a *Botium Toys* não possui todos os controles adequados em vigor e pode não estar totalmente em conformidade com as regulamentações e normas dos EUA e internacionais. 
**Melhores práticas de controle** 
A primeira das cinco funções do NIST CSF é Identificar. A Botium Toys precisará dedicar recursos para identificar ativos para que possam ser gerenciados adequadamente. Além disso, será necessário classificar os ativos existentes e determinar o impacto da perda desses ativos, incluindo sistemas, na continuidade dos negócios. 
**Pontuação de risco** 
Em uma escala de 1 a 10, a pontuação de risco é 8, o que é bastante alto. Isso se deve à falta de controles e adesão às melhores práticas de conformidade.

**4. Comentários adicionais** 
O impacto potencial da perda de um ativo é classificado como médio, pois o departamento de TI não sabe quais ativos estariam em risco. O risco para os ativos ou multas de órgãos reguladores é alto porque a Botium Toys não possui todos os controles necessários em vigor e não está aderindo completamente às melhores práticas relacionadas às regulamentações de conformidade que mantêm os dados críticos privados/seguros. Revise os pontos a seguir para detalhes específicos:

- Atualmente, todos os funcionários da Botium Toys têm acesso a dados armazenados internamente e podem acessar dados de titulares de cartões e informações pessoais identificáveis (PII/SPII) dos clientes. 
- A criptografia não é utilizada atualmente para garantir a confidencialidade das informações de cartão de crédito dos clientes que são aceitas, processadas, transmitidas e armazenadas localmente no banco de dados interno da empresa. 
- Controles de acesso relacionados ao princípio do menor privilégio e à separação de funções não foram implementados. 
- O departamento de TI garantiu a disponibilidade e integrou controles para garantir a integridade dos dados. 
- O departamento de TI possui um firewall que bloqueia o tráfego com base em um conjunto de regras de segurança devidamente definidas. 
- O software antivírus está instalado e é monitorado regularmente pelo departamento de TI. 
- O departamento de TI não instalou um sistema de detecção de intrusão (IDS). 
- Não há planos de recuperação de desastres atualmente em vigor, e a empresa não possui backups de dados críticos. 
- O departamento de TI estabeleceu um plano para notificar os clientes da UE em até 72 horas, caso ocorra uma violação de segurança. Além disso, políticas, procedimentos e processos de privacidade foram desenvolvidos e são aplicados entre os membros do departamento de TI e outros funcionários para documentar e manter os dados adequadamente. 
- Embora exista uma política de senhas, seus requisitos são mínimos e não estão em conformidade com os requisitos atuais de complexidade mínima de senhas (por exemplo, pelo menos oito caracteres, uma combinação de letras e pelo menos um número; caracteres especiais). 
- Não existe um sistema centralizado de gerenciamento de senhas que imponha os requisitos mínimos da política de senhas, o que às vezes afeta a produtividade quando funcionários/fornecedores enviam um ticket para o departamento de TI para recuperar ou redefinir uma senha. 
- Embora os sistemas legados sejam monitorados e mantidos, não há um cronograma regular para essas tarefas, e os métodos de intervenção não são claros. 
- A localização física da loja, que inclui os escritórios principais da Botium Toys, a loja e o depósito de produtos, possui fechaduras suficientes, sistemas atualizados de vigilância por circuito fechado de televisão (CCTV), bem como sistemas de detecção e prevenção de incêndios em funcionamento.


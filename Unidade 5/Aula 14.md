# Aula 14 – Segurança da Informação: Conceitos, Atributos e Ameaças

## Lucas Barreto RA: 22608058

## Objetivo
Compreender os conceitos fundamentais da segurança da informação, identificar seus principais atributos e reconhecer ameaças comuns, aplicando os conhecimentos em estudo de caso prático.

## Práticas de laboratório de informática
Cada grupo deve incluir neste repositório:

### 1. Conceitos Fundamentais
- Definição de Segurança da Informação (ISO/IEC 27000:2018)
Segundo a norma estipulada pela ISO/IEC 27000:2018, a Segurança da Informação é definida como a preservação da confidencialidade, integridade e disponibilidade da informação. Adicionalmente, outras propriedades como autenticidade, responsabilidade, não-repúdio e confiabilidade também podem estar envolvidas.

- Explicação dos atributos principais:
  - **Confidencialidade**: Garante que a informação seja acessível apenas por pessoas explicitamente autorizadas. Evita o vazamento de dados sensíveis e o acesso de terceiros mal-intencionados.
  - **Integridade**: Garante que a informação seja mantida em seu estado original, protegendo-a contra modificações, exclusões ou corrupções não autorizadas durante o armazenamento ou transmissão.
  - **Disponibilidade**: Garante que os usuários autorizados tenham acesso contínuo e confiável à informação e aos sistemas de comunicação sempre que necessário.
  - **Privacidade**: Relaciona-se ao direito do indivíduo de controlar como seus dados pessoais são coletados, armazenados e compartilhados, assegurando a conformidade com leis de proteção de dados

### 2. Ameaças e Vulnerabilidades
**Exemplos de Ameaças Digitais**
- Phishing: Engenharia social via e-mails, SMS ou mensagens falsas que induzem o usuário a clicar em links maliciosos ou entregar credenciais confidenciais.
- Malware: Softwares maliciosos (vírus, cavalos de troia, ransomware) projetados para infiltrar, danificar ou sequestrar sistemas.
**Vulnerabilidades Técnicas e Humanas**
- Vulnerabilidades Técnicas: Sistemas operacionais desatualizados, falta de firewalls, softwares sem patches de correção e brechas no código de aplicações.
- Vulnerabilidades Humanas: Falta de treinamento em cibersegurança, uso de senhas fracas ou compartilhadas, e a ingenuidade do usuário ao abrir anexos suspeitos.
**Impactos Ponteciais**
- Prejuízos Financeiros: Custos com resgates, multas regulatórias e perda de faturamento por sistemas fora do ar.
- Danos à Reputação: Perda de confiança por parte dos clientes e desvalorização da marca no mercado.
- Interrupção Operacional: Paralisia total ou parcial das atividades práticas da empresa devido ao bloqueio de sistemas vitais.
  
### 3. Estudo de Cenário 
- **Opção A – Relatório sobre ataque cibernético real: O Ataque do Ransomware WannaCry (2017)**
  - **Contexto do ataque:** *Em maio de 2017, um ataque global de ransomware em larga escala atingiu mais de 200 mil computadores em cerca de 150 países. O ataque afetou severamente instituições críticas, incluindo o Serviço Nacional de Saúde (NHS) do Reino Unido, empresas de telecomunicações e grandes montadoras de veículos.*
  - **Vulnerabilidade explorada:** *O WannaCry explorou uma vulnerabilidade técnica no protocolo SMBv1 (Server Message Block) de sistemas operacionais Microsoft Windows. Essa falha, conhecida como EternalBlue (que havia sido descoberta e vazada da NSA), permitia que o malware se propagasse lateralmente de forma automática por redes locais sem qualquer interação do usuário.*
  - **Impactos causados:** *O vírus criptografou os dados dos discos rígidos e exigiu o pagamento de um resgate em Bitcoins. Hospitais britânicos tiveram que recusar pacientes e cancelar cirurgias porque perderam o acesso aos prontuários médicos. O prejuízo global estimado foi de bilhões de dólares devido à interrupção de serviços e custos de recuperação.*
  - **Medidas de mitigação aplicadas ou recomendadas:**
  - **Aplicação de Patches:** *Instalação imediata da atualização de segurança disponibilizada pela Microsoft (MS17-010) que corrigia a falha.*
  - **Desativação de Protocolos Obsoletos:** *Desativar completamente o suporte ao protocolo antigo SMBv1 nos sistemas.*
  - **Política de Backups Eficientes:** *Manter rotinas de backup offline (3-2-1) para garantir a restauração dos dados sem a necessidade de pagar resgates.*
  - ** Segmentação de Rede:** *Isolar setores críticos da rede para impedir que um malware se espalhe para outros computadores da organização.*

  ### 4. Reflexão Individual
  - Por que o fator humano é considerado o elo mais frágil da Segurança da Informação?
  - No campo da Segurança da Informação, empresas investem constantemente em tecnologias avançadas para proteger seus dados e sistemas. Firewalls, antivírus inteligentes, criptografia e ferramentas de monitoramento            representam importantes camadas de defesa contra ameaças digitais. Entretanto, mesmo a infraestrutura mais sofisticada pode ser comprometida por um único fator: o comportamento humano.
  - A vulnerabilidade das pessoas não está relacionada à falta de capacidade ou conhecimento, mas às características naturais da psicologia humana. Diferentemente dos sistemas computacionais, que operam com base em regras     e protocolos definidos, os indivíduos são influenciados por emoções, hábitos e circunstâncias. Sentimentos como urgência, curiosidade, medo, confiança e empatia são frequentemente explorados por criminosos por meio de     técnicas de Engenharia Social.
  - Ataques desse tipo procuram manipular usuários para que realizem ações que comprometam a segurança da organização. Um colaborador pode ignorar um e-mail suspeito comum, mas acabar abrindo um anexo com um título            alarmante ou fornecer informações sensíveis a alguém que se apresenta como membro da equipe de suporte técnico.

  ### Fonte: https://www.cloudflare.com/pt-br/learning/security/ransomware/wannacry-ransomware/

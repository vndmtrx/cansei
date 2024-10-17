# Aviso Legal - Projeto CANSEI

## 1. Declaração de Independência e Escopo do Projeto

1.1. Este projeto, denominado "Construção Automatizada e Normatizada do SEI" (CANSEI), doravante referido como "o Projeto", é uma iniciativa independente desenvolvida sem qualquer vínculo oficial, afiliação, endosso ou patrocínio do Tribunal Regional Federal da 4ª Região (TRF4) ou de quaisquer entidades oficiais responsáveis pelo desenvolvimento ou distribuição do Sistema Eletrônico de Informações (SEI).

1.2. O Sistema Eletrônico de Informações (SEI) é uma plataforma de processo eletrônico desenvolvida pelo TRF4. O SEI é amplamente utilizado na administração pública brasileira para a gestão de processos e documentos eletrônicos, promovendo a eficiência, transparência e economicidade na gestão pública. O SEI é um software proprietário, cujo licenciamento e distribuição são controlados pelo TRF4.

1.3. O Projeto CANSEI tem como objetivo fornecer uma solução de automação para o processo de instalação, configuração e implantação do SEI, seguindo as melhores práticas de DevOps. O CANSEI inclui:

1. Scripts Ansible para automação da configuração de infraestrutura;
2. Dockerfiles e docker-compose para criação de containers otimizados para o SEI para ambientes Docker e Docker Swarm;
3. Definições de Pods e Deployments para orquestração em ambientes Kubernetes;
4. Scripts auxiliares para manipulação de configurações e variáveis de ambiente.

1.4. É fundamental ressaltar que o Projeto CANSEI não inclui, distribui ou modifica o software SEI em si. O CANSEI é uma camada de automação que trabalha em conjunto com o SEI, mas não altera seu código-fonte ou funcionalidade intrínseca. 

1.5. O CANSEI visa simplificar e padronizar o processo de implantação do SEI, permitindo:

1. Redução do tempo de implantação;
2. Minimização de erros humanos durante a configuração;
3. Facilitação de atualizações e manutenções;
4. Melhoria na portabilidade entre diferentes ambientes de infraestrutura;
5. Aumento da eficiência operacional para equipes de TI que gerenciam instâncias do SEI.

1.6. Os usuários deste Projeto são expressamente informados de que a obtenção do software SEI deve ser realizada exclusivamente através dos canais oficiais designados pelo TRF4, em conformidade com os termos de uso e licenciamento estabelecidos por aquela instituição. O CANSEI não substitui, modifica ou elimina qualquer requisito ou processo oficial estabelecido pelo TRF4 para a implementação e uso do SEI.

## 2. Compatibilidade e Verificação de Integridade

2.1. O Projeto CANSEI é projetado para ser compatível com diversas versões do SEI. A compatibilidade específica com cada versão é documentada nos arquivos de configuração e na documentação do projeto.

2.2. Para garantir a integridade e autenticidade dos componentes do SEI utilizados no processo de implantação, o CANSEI implementa verificações de integridade baseadas em hash. Este processo assegura que:

1. A versão correta do SEI está sendo utilizada;
2. Os arquivos do SEI não foram alterados ou corrompidos durante o processo de download ou armazenamento;
3. A instalação está em conformidade com a versão oficial distribuída pelo TRF4.

2.3. Os usuários são responsáveis por verificar e garantir que estão utilizando a versão do CANSEI compatível com a versão do SEI que desejam implantar. Informações detalhadas sobre compatibilidade e procedimentos de verificação estão disponíveis na documentação do projeto.

2.4. O CANSEI é regularmente atualizado para manter compatibilidade com as novas versões do SEI lançadas pelo TRF4. No entanto, pode haver um intervalo entre o lançamento de uma nova versão do SEI e a atualização correspondente do CANSEI. Os usuários devem sempre consultar a documentação mais recente do projeto para informações sobre compatibilidade.

## 3. Licenciamento e Direitos Autorais

3.1. O Projeto CANSEI, incluindo todos os scripts, configurações e documentação associada, é licenciado sob os termos da GNU Affero General Public License versão 3 (AGPLv3), conforme publicada pela Free Software Foundation.

3.2. Nos termos da AGPLv3 e em consonância com a Lei nº 9.610/1998 (Lei de Direitos Autorais), os usuários têm o direito de copiar, modificar e distribuir o código deste Projeto, desde que mantenham o mesmo licenciamento para obras derivadas e cumpram todas as obrigações estabelecidas na licença.

3.3. Em conformidade com o artigo 7º da AGPLv3 e o princípio da liberdade contratual previsto no artigo 421 do Código Civil Brasileiro, qualquer termo adicional ou disposição divergente oferecida será considerada uma proposta de modificação da licença, não tendo efeito legal na ausência de aceitação expressa pelos detentores dos direitos autorais do Projeto.

## 4. Responsabilidades e Garantias

4.1. Em observância ao artigo 8º do Marco Civil da Internet (Lei nº 12.965/2014) e ao artigo 15 da AGPLv3, os scripts, configurações e qualquer outro material fornecido como parte deste Projeto são disponibilizados "no estado em que se encontram", sem garantias de qualquer natureza, sejam expressas ou implícitas.

4.2. Os criadores, mantenedores e colaboradores deste Projeto não se responsabilizam por quaisquer danos diretos, indiretos, incidentais, especiais, exemplares ou consequenciais (incluindo, mas não se limitando a, aquisição de bens ou serviços substitutos, perda de uso, dados ou lucros, ou interrupção de negócios) decorrentes do uso ou da impossibilidade de uso deste Projeto, mesmo que tenham sido avisados da possibilidade de tais danos.

4.3. Conforme o artigo 43, §1º do Marco Civil da Internet, os desenvolvedores e mantenedores deste Projeto não serão responsabilizados por danos decorrentes de conteúdo gerado por terceiros.

## 5. Obrigações do Usuário

5.1. Ao utilizar este Projeto, o usuário se compromete a:

1. Obter o software SEI exclusivamente através dos canais oficiais designados pelo TRF4;
2. Cumprir integralmente os termos de uso e licenciamento do SEI estabelecidos pelo TRF4;
3. Respeitar os termos da licença AGPLv3 aplicável a este Projeto;
4. Em caso de modificação e uso dos scripts em rede, disponibilizar o código-fonte completo das versões modificadas, conforme exigido pela AGPLv3.

5.2. O não cumprimento destas obrigações pode resultar em violação de direitos autorais e outras implicações legais.

## 6. Disposições Gerais

6.1. Este aviso legal está em conformidade com a legislação brasileira, incluindo, mas não se limitando à Lei de Direitos Autorais (Lei nº 9.610/1998), o Marco Civil da Internet (Lei nº 12.965/2014) e o Código Civil Brasileiro (Lei nº 10.406/2002).

6.2. Caso qualquer disposição deste aviso legal seja considerada inválida ou inexequível, as demais disposições permanecerão em pleno vigor e efeito.

6.3. A tolerância quanto ao descumprimento de qualquer obrigação prevista neste aviso não implicará em novação ou renúncia de direitos.

## 7. Foro e Jurisdição

7.1. Fica eleito o foro da Comarca de Uberlândia/MG para dirimir quaisquer controvérsias decorrentes deste Projeto ou deste aviso legal, sem prejuízo de outro porventura competente.

7.2. Em caso de litígio, a parte vencida arcará com os custos e despesas processuais, bem como os honorários advocatícios razoáveis da parte vencedora, nos termos do artigo 85 do Código de Processo Civil Brasileiro.

---

Data da última atualização: 17 de outubro de 2024

Para mais informações ou esclarecimentos, entre em contato através do e-mail [vndmtrx@duck.com](mailto:vndmtrx@duck.com).

## Referências Legislativas

BRASIL. **Lei nº 9.610, de 19 de fevereiro de 1998**. Altera, atualiza e consolida a legislação sobre direitos autorais e dá outras providências. *Diário Oficial da União*, Brasília, DF, 20 fev. 1998. Disponível em: <http://www.planalto.gov.br/ccivil_03/leis/l9610.htm>. Acesso em: 17 out. 2024.

BRASIL. **Lei nº 10.406, de 10 de janeiro de 2002**. Institui o Código Civil. *Diário Oficial da União*, Brasília, DF, 11 jan. 2002. Disponível em: <http://www.planalto.gov.br/ccivil_03/leis/2002/l10406compilada.htm>. Acesso em: 17 out. 2024.

BRASIL. **Lei nº 12.965, de 23 de abril de 2014**. Estabelece princípios, garantias, direitos e deveres para o uso da Internet no Brasil. *Diário Oficial da União*, Brasília, DF, 24 abr. 2014. Disponível em: <http://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l12965.htm>. Acesso em: 17 out. 2024.

BRASIL. **Lei nº 13.105, de 16 de março de 2015**. Código de Processo Civil. *Diário Oficial da União*, Brasília, DF, 17 mar. 2015. Disponível em: <http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2015/lei/l13105.htm>. Acesso em: 17 out. 2024.

FREE SOFTWARE FOUNDATION. **GNU Affero General Public License**. Versão 3, 19 nov. 2007. Disponível em: <https://www.gnu.org/licenses/agpl-3.0.html>. Acesso em: 17 out. 2024.
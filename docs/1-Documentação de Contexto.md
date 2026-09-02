# Introdução

O acesso à saúde é um direito fundamental e deve ser garantido de forma igualitária a toda a população. Entretanto, apesar da existência de serviços de atendimento médico gratuito, diversos fatores ainda dificultam o acesso de parte da população às consultas. Entre esses fatores, destacam-se as dificuldades relacionadas ao transporte, à distância entre a residência do paciente e o local de atendimento e às condições financeiras para realizar o deslocamento.

Nesse contexto, a PUC Minas enfrenta um problema relacionado ao não comparecimento de pacientes às consultas médicas gratuitas oferecidas pela instituição. Embora o atendimento seja disponibilizado sem custo, uma parcela dos pacientes não consegue comparecer devido às barreiras de deslocamento. Essa situação prejudica tanto os pacientes, que deixam de receber o acompanhamento médico necessário, quanto a própria instituição, que disponibiliza horários e recursos que acabam não sendo utilizados.

Diante desse cenário, é proposto a implantação de cabines de teleconsulta em unidades de saúde da região, permitindo que os pacientes tenham acesso ao atendimento médico em locais mais próximos de suas residências. A proposta busca utilizar a tecnologia como ferramenta para aproximar pacientes e profissionais de saúde, reduzindo a necessidade de deslocamentos e, consequentemente, os custos e dificuldades associados ao atendimento presencial.

Para que a solução seja implementada de maneira adequada, o projeto contempla a definição dos requisitos de hardware e tratamento acústico das cabines, a análise da infraestrutura de rede necessária para a realização das teleconsultas e a estimativa da capacidade de atendimento de cada cabine. Dessa forma, pretende-se desenvolver uma solução viável e dimensionada de acordo com a demanda existente.

Além de contribuir para a redução das faltas às consultas, a iniciativa está relacionada aos Objetivos de Desenvolvimento Sustentável (ODS) da Agenda 2030, especialmente o ODS 3, que busca assegurar uma vida saudável e promover o bem-estar para todos, e o ODS 10, voltado à redução das desigualdades. Assim, a proposta é utilizar a tecnologia para ampliar o acesso à saúde e contribuir para um atendimento mais acessível e inclusivo.

## Problema
 Pessoas em diversas regiões do Brasil não recebem atendimento médico adequado devido à falta de acesso a consultas. A PUC está enfrentando um problema em que pacientes marcam consultas médicas gratuitas, mas grande parte deles não comparece. Muitas vezes, o motivo é que essas pessoas moram longe do local de atendimento e não possuem condições de se deslocar até lá, seja pela falta de acesso a transporte, seja pela falta de condições financeiras para custeá-lo. 
 Esse cenário evidencia que a localização das clínicas é um fator determinante para o não comparecimento dos pacientes, uma vez que a distância entre a residência e o local de atendimento pode dificultar o acesso, mesmo quando a consulta é gratuita.

## Objetivos

Objetivo principal
 
  Implantação de cabines de teleconsulta em unidades de saúde da região, aproximando o atendimento médico dos pacientes que enfrentam barreiras de deslocamento e financeiro.
  
Objetivos específicos

a) Identificar e especificar os requisitos mínimos de hardware e de tratamento acústico das cabines, definindo uma configuração padrão que atenda à necessidade clínica sem superdimensionar componentes;

b) Mensurar o consumo de banda larga de uma teleconsulta real, utilizando o aplicativo PEC como cenário de teste, a fim de dimensionar a infraestrutura de rede necessária em cada unidade;

c) Estimar a capacidade de atendimento por cabine, em número de pacientes por turno e por dia, definindo quantas cabines seriam necessárias para absorver a demanda atual, considerando o absenteísmo de cada região:

Zona Leste	10;

Zona Oeste	9;

Zona Sul	8;

Centro	6;

Zona Norte	6.

Total urbano:39



## Justificativa

  O acesso à saúde é um direito de todos e, por isso, existe o acesso gratuito à medicina que, no caso das pessoas de baixa renda, é garantido pelo SUS. Nesse contexto, diversas regiões do Brasil contam com hospitais que oferecem esse tipo de atendimento, como é o caso de Poços de Caldas, na faculdade PUC. Apesar disso, observa-se que muitos pacientes não comparecem às consultas marcadas.

Segundo estudos publicados pela National Library of Medicine, "as barreiras de transporte são frequentemente citadas como obstáculos ao acesso à saúde. Essas barreiras levam ao reagendamento ou à perda de consultas, ao atraso no atendimento e à falta ou ao atraso no uso de medicamentos" [1]. Nos Estados Unidos, pesquisas mostraram que essas barreiras afetam o acesso à saúde em uma proporção que varia entre 3% e 67% da população amostrada, evidenciando a relevância do problema mesmo em diferentes contextos e realidades. No Brasil, esse cenário também se confirma: de acordo com o Journal of School of Nursing – University of São Paulo, 29% das faltas às consultas ocorrem por causa de dificuldades relacionadas aos meios de transporte, enquanto 16,3% são motivadas por problemas financeiros [2], reforçando que tanto o deslocamento quanto o custo do atendimento presencial são fatores determinantes para o absenteísmo nos serviços de saúde.

Diante desse cenário, torna-se essencial buscar soluções que reduzam essas dificuldades, uma vez que a ODS 3 da Agenda 2030 estabelece que todos devem ter acesso a um bem-estar de qualidade [3]. Assim, desenvolver um projeto voltado à diminuição desses desafios pode contribuir diretamente para melhorar a qualidade de vida da população brasileira.

Nesse sentido, a telemedicina se apresenta como uma alternativa viável para reduzir o número de faltas às consultas médicas, uma vez que elimina a necessidade de deslocamento e diminui os custos associados ao atendimento presencial — fatores que, juntos, respondem por quase metade das ausências registradas. Essa modalidade de atendimento é especialmente importante porque possibilita o acompanhamento contínuo de pacientes que, de outra forma, adiariam ou deixariam de buscar cuidados médicos, evitando o agravamento de doenças e reduzindo a sobrecarga dos serviços de saúde presenciais. Além disso, a telemedicina proporciona mais comodidade e flexibilidade de horários, fatores que aumentam a adesão dos pacientes ao tratamento e favorecem um cuidado mais preventivo do que corretivo. Ao aproximar o atendimento de saúde daqueles que enfrentam barreiras de transporte e de renda, o projeto contribui não apenas para o ODS 3, mas também para o ODS 10 da Agenda 2030, referente à redução das desigualdades [4], garantindo que pessoas em situação de vulnerabilidade socioeconômica tenham as mesmas oportunidades de acompanhamento médico que a população em geral. Dessa forma, a telemedicina representa um passo concreto rumo a uma sociedade mais justa, inclusiva e saudável.

## Público-Alvo


O público-alvo desta ação é composto por pacientes atendidos pelo SUS, especialmente os vinculados a hospitais universitários como a PUC de Poços de Caldas. Esse grupo apresenta perfis variados quanto à idade, condição socioeconômica e alfabetização digital, refletindo a diversidade de pessoas que dependem do sistema público de saúde para acompanhamento médico.

Trata-se de pessoas já habituadas aos processos do SUS, mas que enfrentam barreiras recorrentes de transporte, condição financeira para comparecer às consultas, e principalmente a dificuldade com o uso de tecnologias, fatores que juntos respondem por quase metade das faltas registradas. Esse público também se relaciona com profissionais de saúde (médicos, enfermeiros e equipe administrativa), cuja adesão à ferramenta é igualmente importante. Compreender esse perfil é essencial para desenvolver uma solução acessível, alinhada aos objetivos da ODS 3 e da ODS 10 da Agenda 2030.

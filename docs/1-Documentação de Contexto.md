# Introdução

O acesso à saúde é um direito fundamental e deve ser garantido de forma igualitária a toda a população. Entretanto, apesar da existência de serviços de atendimento médico gratuito, diversos fatores ainda dificultam o acesso de parte da população às consultas. Entre esses fatores, destacam-se as dificuldades relacionadas ao transporte, à distância entre a residência do paciente e o local de atendimento e às condições financeiras para realizar o deslocamento.

Nesse contexto, a PUC Minas enfrenta um problema relacionado ao não comparecimento de pacientes às consultas médicas gratuitas oferecidas pela instituição. Embora o atendimento seja disponibilizado sem custo, uma parcela dos pacientes não consegue comparecer devido às barreiras de deslocamento. Essa situação prejudica tanto os pacientes, que deixam de receber o acompanhamento médico necessário, quanto a própria instituição, que disponibiliza horários e recursos que acabam não sendo utilizados.

Este projeto tem origem em uma demanda apresentada pelo prof. Fabiano, professor responsável pela tecnologia do curso de medicina da faculdade PUC MINAS Poços de Caldas, que relatou (Reunião realizada com o professor Fabiano no dia 28 de agosto de 2026) o problema do não comparecimento de pacientes às consultas médicas gratuitas oferecidas pela instituição e propôs a utilização de cabines de teleconsulta como alternativa para reduzi-lo. 

Para que a solução seja implementada de maneira adequada, o projeto contempla a definição dos requisitos de hardware e físicos, a análise da infraestrutura de rede necessária para a realização das teleconsultas e a estimativa da capacidade de atendimento de cada cabine. Dessa forma, pretende-se desenvolver uma solução viável e dimensionada de acordo com a demanda existente.

Além de contribuir para a redução das faltas às consultas, a iniciativa está relacionada aos Objetivos de Desenvolvimento Sustentável (ODS) da Agenda 2030, especialmente o ODS 3, que busca assegurar uma vida saudável e promover o bem-estar para todos, e o ODS 10, voltado à redução das desigualdades. Assim, a proposta é utilizar a tecnologia para ampliar o acesso à saúde e contribuir para um atendimento mais acessível e inclusivo.

## Problema
 Pessoas em diversas regiões do Brasil não recebem atendimento médico adequado devido à falta de acesso a consultas. A PUC está enfrentando um problema em que pacientes marcam consultas médicas gratuitas, mas grande parte deles não comparece. Muitas vezes, o motivo é que essas pessoas moram longe do local de atendimento e não possuem condições de se deslocar até lá, seja pela falta de acesso a transporte, seja pela falta de condições financeiras para custeá-lo. 
 Esse cenário evidencia que a localização das clínicas é um fator determinante para o não comparecimento dos pacientes, uma vez que a distância entre a residência e o local de atendimento pode dificultar o acesso, mesmo quando a consulta é gratuita.

## Objetivos

Objetivo principal
 
  Auxiliar no estudo sobre requisitos técnicos e físicos para a implantação de cabines de teleconsulta em unidades de saúde da região, aproximando o atendimento médico dos pacientes que enfrentam barreiras de deslocamento e financeiro.
  
Objetivos específicos

a) Pesquisar e especificar os requisitos do espaço físico destinado à cabine (dimensões mínimas, ventilação, iluminação, acessibilidade), definindo um modelo de ambiente que possa ser replicado nas UBSs;

b) Identificar e especificar os requisitos mínimos de hardware, definindo uma configuração padrão que atenda à necessidade clínica sem superdimensionar componentes;

c) Mensurar o consumo de banda de uma teleconsulta, utilizando o aplicativo e-SUS APS como cenário de teste, a fim de estimar a infraestrutura de rede mínima necessária em cada unidade.



## Justificativa

  O acesso à saúde é um direito de todos e, para as pessoas de baixa renda, é garantido pelo Sistema Único de Saúde (SUS). Em Poços de Caldas, o município conta com 39 Unidades Básicas de Saúde (UBS) disponíveis, além dos atendimentos realizados no âmbito da PUC Minas. Apesar dessa oferta, o não comparecimento a consultas agendadas representa vagas de atendimento não aproveitadas. Segundo dados divulgados pela Secretaria Municipal de Saúde, entre janeiro e agosto de 2025 foram agendadas 93.725 consultas médicas na rede pública do município, das quais 71.784 foram realizadas, o que corresponde a um índice de absenteísmo de 23,41%, ou seja, quase uma a cada quatro consultas não ocorreu por ausência do paciente [1].

 A literatura indica que o deslocamento e o custo do atendimento estão entre os fatores associados às faltas. Segundo estudos publicados pela National Library of Medicine, "as barreiras de transporte são frequentemente citadas como obstáculos ao acesso à saúde. Essas barreiras levam ao reagendamento ou à perda de consultas, ao atraso no atendimento e à falta ou ao atraso no uso de medicamentos" [2]. Nos Estados Unidos, pesquisas mostraram que essas barreiras afetam o acesso à saúde em uma proporção que varia entre 3% e 67% da população amostrada [2]. No Brasil, segundo o Journal of School of Nursing, da Universidade de São Paulo, 29% das faltas às consultas estão relacionadas a dificuldades com meios de transporte e 16,3% a problemas financeiros [3]. Esses percentuais não explicam, por si só, as faltas registradas em Poços de Caldas, mas indicam que tais barreiras existem e podem estar presentes no contexto local. Por isso, são utilizados aqui como sustentação externa, enquanto os dados municipais caracterizam a realidade da região.

 Nesse cenário, a ODS 3 da Agenda 2030 estabelece a garantia de uma vida saudável e a promoção do bem-estar para todos [4], o que reforça a importância de buscar soluções que ampliem o acesso aos serviços de saúde. A telemedicina é uma das alternativas que podem ser exploradas nesse sentido, pois permite que o atendimento seja realizado a distância, com o paciente e o médico em locais diferentes. Cabe ao projeto verificar, no contexto local, as condições técnicas e físicas necessárias para que esse modelo seja viável.

 Nessa perspectiva, o projeto propõe a instalação de cabines de teleconsulta em unidades de saúde da região, com o objetivo de aproximar o atendimento da residência do paciente e reduzir seus deslocamentos. A cabine não elimina a necessidade de ir até a unidade em que estiver instalada, mas pode diminuir a distância percorrida, sobretudo para pessoas com dificuldade de locomoção. Dessa forma, a proposta se alinha também à ODS 10 da Agenda 2030, referente à redução das desigualdades [5], ao buscar ampliar as oportunidades de acompanhamento médico para quem enfrenta mais barreiras de acesso.

## Público-Alvo


O público-alvo desta ação é composto por pacientes atendidos pelo SUS, especialmente os vinculados a hospitais universitários como a PUC de Poços de Caldas. Esse grupo apresenta perfis variados quanto à idade, condição socioeconômica e alfabetização digital, refletindo a diversidade de pessoas que dependem do sistema público de saúde para acompanhamento médico.

Trata-se de pessoas já habituadas aos processos do SUS, mas que enfrentam barreiras recorrentes de transporte, condição financeira para comparecer às consultas, e principalmente a dificuldade com o uso de tecnologias, fatores que juntos respondem por quase metade das faltas registradas. Esse público também se relaciona com profissionais de saúde (médicos, enfermeiros e equipe administrativa), cuja adesão à ferramenta é igualmente importante. Compreender esse perfil é essencial para desenvolver uma solução acessível, alinhada aos objetivos da ODS 3 e da ODS 10 da Agenda 2030.

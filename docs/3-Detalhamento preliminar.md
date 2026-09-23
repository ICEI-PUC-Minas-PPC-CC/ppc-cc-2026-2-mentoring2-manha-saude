# Detalhamento preliminar

## lista de software

###SOFTWARE 1:

Nome: Portal Telemedicina

Link:[(https://portaltelemedicina.com.br)](https://portaltelemedicina.com.br/)

Preço: Cerca de R$55.000/ano para licença institucional, suporte e serviços associados.

O que oferece: A Portal oferece teleconsulta, telediagnóstico, integração entre sistemas e integração direta com aparelhos médicos.A plataforma consegue OPERAR com cerca de 90% dos equipamentos presentes no mercado e pode apresentar informações com prontuários, laboratórios, LIS e PACS.

Requisitos mínimos (software e infraestrutura):

Computador/notebook	16 GB RAM, SSD 512 GB    	R$ 5.500

Monitor 24" Full HD	    R$ 900

Webcam Full HD	1080p	    R$ 650

Headset profissional, microfone com redução de ruído    	R$ 700

Nobreak		R$ 850

Rede/cabos/adaptadores	  	R$ 500

Estetoscópio digital	R$ 5.500

Otoscópio digital	R$ 6.500

Monitor multiparamétrico	R$ 12.000

ECG 12 derivações	R$ 7.000

TOTAL	aproximadamente R$ 45.000

###SOFTWARE 2:

Nome: Conexa Saúde

Link:https://www.conexasaude.com.br/

Preço: Para o plano de 100 usuários, o custo seria de aproximadamente R$ 18.000

O que oferece: Teleconsulta por vídeo, pronto atendimento digital, consultas com especialistas, prontuário eletrônico, triagem/acompanhamento do paciente e armazenamento de informações clínicas. A plataforma mantém no prontuário informações como comorbidades, medicamentos, alergias e histórico de especialidades, além dos recursos de câmera e microfone usados na consulta.

Requisitos mínimos (software e infraestrutura):
Software Conexa Saúde	Teleconsulta, prontuário e atendimento digital		R$ 1.490/mês*

Computador/notebook	16 GB RAM, SSD 512 GB    	R$ 4.800

Monitor 24" Full HD		R$ 700

Webcam Full HD	1080p    	R$ 450

Headset USB	Microfone com boa redução de ruído    	R$ 350

Nobreak     	R$ 740

Rede/cabeamento	    	R$ 300

Internet fibra	  	≈ R$ 300/mês

Estetoscópio digital Eko CORE 500	Digital    	≈ R$ 5.359

Otoscópio Digital SyncVision Full HD    	≈ R$ 6.500

Monitor multiparamétrico	ECG    	≈ R$ 7.000

Eletrocardiógrafo 12 derivações	ECG digital compatível com PC	    ≈ R$ 7.500

TOTAL aproximadamente R$ 35.000

###SOFTWARE 3:

Nome: Jitsi Meet (instalação própria, self-hosted)

Link: https://jitsi.org/jitsi-meet/ (requisitos: https://jitsi.github.io/handbook/docs/devops-guide/devops-guide-requirements)

Preço: gratuito e de código aberto. O custo real é o servidor, porque a PUC teria que hospedar em máquina própria ou alugar uma.

O que oferece: videoconferência pelo navegador, sem instalar nada além dele no computador de quem participa. Tem compartilhamento de tela, chat e gravação. O ponto forte para o projeto é que a instituição fica com o controle total dos dados, da segurança e das funcionalidades, o que ajuda na LGPD. Por ser código aberto, o grupo pode alterar o sistema, ao contrário do e-SUS APS.

Requisitos mínimos (software e infraestrutura):

Servidor: o recomendado é 8 GB de RAM. Para reuniões pequenas dá com 4 GB, e 2 GB só para testes.
Processador: processador muito fraco prejudica o funcionamento em tempo real. Em servidor virtual (VPS), prefira CPU dedicada.
Sistema operacional: distribuição Linux suportada, como Debian ou Ubuntu.
Gravação (opcional, módulo Jibri): gravar em 1280×720 exige pelo menos 8 GB de RAM por reunião gravada, e disco SSD.
Internet: em 720p cada participante consome cerca de 2,5 Mbps, e em 1080p de 4 a 5 Mbps.
Usuário final: apenas navegador atualizado, câmera e microfone.

SOFTWARE 4:

Nome: iClinic (prontuário eletrônico com Teleconsulta)

Link: https://iclinic.com.br/funcionalidades/teleconsulta/ (preços: https://iclinic.com.br/precos/)

Preço: cobrado por profissional por mês. Em agosto de 2026 os valores eram R$ 99 no Starter, R$ 129 no Plus, R$ 169 no Pro e R$ 299 no Premium. A teleconsulta ilimitada só vem no Premium. Nos outros planos ela sai por mais R$ 35 por mês a cada 10 atendimentos. Esses preços vêm de sites comparativos, então confirma na página oficial antes de entregar.

O que oferece:

Agenda, cadastro de pacientes, prontuário eletrônico, prescrição e recursos administrativos.
Durante a teleconsulta, o prontuário fica aberto e dá para compartilhar a tela com o paciente.
Gravações opcionais, que podem ser anexadas ao prontuário.
Lembretes automáticos de consulta pelo WhatsApp.
Documentos médicos com validade jurídica.
Prontuário personalizável por especialidade.

Requisitos mínimos (software e infraestrutura): é um sistema em nuvem, acessado de qualquer dispositivo, então não precisa de servidor próprio. Na prática, basta computador com navegador atualizado, webcam, microfone e internet estável. Para a internet, pode usar como referência o mínimo do Ministério da Saúde: 10 Mbps de download e 5 Mbps de upload. Não achei uma ficha oficial de requisitos publicada pela iClinic. Se o professor cobrar, vale perguntar ao suporte deles.



## SOFTWARE 5:

Nome: Doutor ao Vivo – Estação de Saúde Digital

Link: https://doutoraovivo.com.br/totem-de-telemedicina/

Preço: Não informado publicamente no site. É necessário entrar em contato com a empresa e solicitar orçamento. Não é gratuito.

O que oferece: Estação para triagem e teleconsulta, com recursos para aferição de pressão arterial, batimentos cardíacos, oxigenação sanguínea e temperatura corporal. Também oferece videoatendimento, prontuário eletrônico, prescrições, exames, atestados, agendamento e integração das informações coletadas durante o atendimento.

Requisitos mínimos (software e infraestrutura): Necessita de conexão com a Internet e utiliza a plataforma própria da Doutor ao Vivo. O software é proprietário, mas permite personalização da identidade visual e integração por API. O site informa a utilização de dispositivos médicos conectados para aferição de sinais vitais, porém não informa publicamente se computador, TV, webcam e microfone são fornecidos separadamente junto com a estação.

## SOFTWARE 6:

Nome: Telemedicina Morsch

Link: https://telemedicinamorsch.com.br/

Preço: Não possui preço único divulgado. O valor varia de acordo com os serviços, quantidade de exames e equipamentos contratados. Alguns equipamentos podem ser disponibilizados em comodato mediante contratação do serviço.

O que oferece: Plataforma de telemedicina, teleconsulta e telediagnóstico. Pode ser utilizada com eletrocardiógrafo, Holter, MAPA de pressão arterial, eletroencefalógrafo e espirômetro. Os exames podem ser enviados pela Internet para análise e emissão de laudos por especialistas.

Requisitos mínimos (software e infraestrutura): É necessário possuir computador ou notebook com acesso à Internet para acessar a plataforma. O sistema funciona online por navegador, utilizando login e senha. O software é proprietário e não há indicação de acesso ao código-fonte. A Morsch pode fornecer equipamentos médicos em comodato, como eletrocardiógrafo, Holter, MAPA, eletroencefalógrafo e espirômetro. Também é possível utilizar equipamentos próprios compatíveis. O site não informa que TV, webcam, microfone ou notebook sejam fornecidos como parte padrão do kit.




















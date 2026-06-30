# mapa-geral-de-redes-notebookLM
Conceitualização de redes na TIC e processos envolvidos a partir de fontes digitais e uso guiado do NotebookLM.

# Introdução e Objetivos
A ideia desse projeto foi basicamente criar um caderno temático para estudos utilizando a ferramenta de IA NotebookLM do Google, onde é possível organizar diferentes fontes selecionadas como banco de dados para o seu projeto e todas as respostas (que podem estar em vários formatos) vão ser baseadas nessas fontes, o que pode ajudar a reduzir alucinações e direcionar o assunto.
O tema que eu escolhi foi redes, protocolos e arquitetura e o objetivo é introduzir e criar uma base sobre os processos e conceitos principais envolvidos na criação e configuração dessas redes.

# Fontes Utilizadas
Tentei usar 4 fontes didáticas e referências técnicas do Google Acadêmico e 1 de um site de conceitulização para garantir uma base confiável.
[aula7.pdf](https://github.com/user-attachments/files/29467371/aula7.pdf)

[v9n3art2.pdf](https://github.com/user-attachments/files/29467365/v9n3art2.pdf)

[TL03 2000 ERI Monteiro.pdf](https://github.com/user-attachments/files/29467353/TL03.2000.ERI.Monteiro.pdf)

[Redes_de_Computadores_e_Internet.pdf](https://github.com/user-attachments/files/29467347/Redes_de_Computadores_e_Internet.pdf)

https://www.opservices.com.br/protocolos-de-rede/

# Prompts
Enviei 3 prompts diferentes, um mais específico do que o outro, abordando diferentes camadas de redes.

1. "Explique o funcionamento das redes de computadores diferenciando seus tipos e topologias, do mais simples ao mais avançado. Apresente em formato de tópicos de maneira acessível e detalhada."
A resposta gerada foi bem simples, abordando os tópicos de Escala, Forma de Conexão, Comutação, Organização em Camadas e Protocolos e Estrutura Avançada. Cada tópico usou de 2 a 4 subtópicos explicados em uma frase cada.

2. "Simulando um técnico experiente em redes, explique detalhadamente os conceitos necessários para a criação e configuração de uma rede, abordando como saber escolher e interconectar as diferentes camadas  utilizadas na integração de redes. Após explicar a teoria, monte um passo a passo descritivo em formato de tópicos explicando como realizar esse processo na prática, em ambientes avançados ou domésticos."
Aqui além da instrução eu já coloquei um contexto, critérios e o formato de saída, mas a resposta se manteve em um padrão parecido. A parte teórica foi uma explicação simples do Modelo TCP/IP e Encapsulamento, enquanto a prática foram 6 passos bem generalistas e que não especificaram os critérios que a pessoa precisa ter.

3. "Tendo como ponto de partida que está explicando para uma pessoa inexperiente, responda como se fosse um professor renomado e experiente na área de TIC e redes os principais tipos de protocolos, como é feita sua configuração e a relação de cada um com o modelo OSI. Apresente também como é feita sua configuração de forma detalhada, ilustrando termos importantes e insights necessários para a compreensão. Desenvolva em formato de tópicos com uma síntese ao final."
O resultado foi mais detalhado e explicativo, abordando os tópicos de O Modelo OSI: O Mapa da Comunicação, Principais Tipos de Protocolos,  Como é feita a Configuração, Termos Importamtes e Insights e Síntese. Deu uma base mais sólida, mas decidi tentar adicionar maior detalhamento e pedir para uma Cadeia de Pensamento para extrair o melhor resultado porque achei que ficou um pouco redundante.
Ficou assim: "Tendo como ponto de partida que está explicando para um estudante inexperiente, responda como se fosse um professor renomado e experiente na área de TIC e redes os principais tipos de protocolos de rede, como é feita sua configuração e a relação de cada um com o modelo OSI. Apresente também como é feita sua programação de forma detalhada e por quais protocolos de gerência, ilustrando termos importantes e insights necessários para a compreensão. Explicite a cadeia de pensamento necessária para um técnico de TIC e redes ao configurar uma rede profissional em um diagnóstico de rede, com foco na detecção de problemas. Desenvolva em formato longo e completo de tópicos com uma síntese em texto ao final."
Tive que especificar bem mais os componentes do prompt, mas acabou que o resultado ainda ficou simplificado, mas melhor direcionado no assunto.

# Resumo Próprio do Assunto
A Tecnologia da Informação e Comunicação é um termo mais geral que descreve todos os recursos utilizados não só para armazenar, mas também transportar informações entre dispositivos, onde a parte de redes é a responsável por transferir esses dados.

Uma rede pode ser classificada por sua extensão, sendo a LAN (Local Area Network) para salas ou prédios e a WAN (Wide Area Network) podendo se extender globalmente, como a própria internet. O wi-fi no geral é uma LAN do tipo WLAN, o que significa que ele pode se propagar sem fios com determinados dispositivos. Também podem ser classificadas quanto à sua topologia, que é como os dispositivos estão conectados fisica ou logicamente, como a em Estrela onde os dispositivos estão conectados a um roteador principal e a Topologia em Malha (Mesh), que tem mais conexões entre dispositivos e é muito mais avançada. O modo de funcionamento é conhecido como Comutação, que hoje em dia o mais comum é a Comutação por Pacotes, onde basicamente os dados requeridos são divididos e podem percorrer diferentes meios para chegar ao destino.

Durante a troca de informações, diferentes camadas vão estar agindo com diferentes funções. Uma maneira de classificar elas é o Modelo OSI, que divide esse processo todo em 7 camadas: Aplicação, Apresentação, Sessão, Transporte, Rede, Enlace e Física. Para que essa comunicação aconteça, são usados os protocolos, que são meios com regras específicas de como esse transporte de informações ocorre. O IP é um protocolo que define o endereço de origem e o endereço de destino de cada pacote e esse processo é chamado de encapsulamento.

Para um técnico fazer um diagnóstico da rede, ele normalmente vai pensar e conferir as camadas do encapsulamento seguindo a ordem inversa, do final ao começo, verificando desde a funcionabilidade de dispositivos físicos até a resposta dos softwares a partir do Prompt de Comando (CMD). Em redes profissionais, ele poderá veificar o protocolo de gerência SNMP.
Termos importantes:

Internet: maior rede de computadores do mundo, formada por diferentes redes menores, físicas e lógicas.

Wi-fi: tecnologia de comunicação sem fio.

Protocolo: conjunto de regras que define como os dispositivos se comunicam.

Roteador: encaminha pacotes entre redes diferentes.

TCP: protocolo de conexão que garante entrega das informações.

DNS: traduz URLs (endereços de páginas de sites) para endereços IP automaticamente.

Host: qualquer dispositivo que está conectado na rede.

Latência: tempo de demora do pacote chegar ao destino.

Ping: ferramenta que mede latência.

Cliente: dispositivo ou programa que solicita o serviço.

Servidor: computador ou programa que oferece serviços.

Handshake: conexão entre cliente e servidor.

Endereço MAC: identificador de um dispositivo físico.

Switch: equipamento físico que decide para qual porta enviar um pacote.

Firewall: filtra o tráfego de pacotes.

Ideias de prompts:
"Atue como um professor universitário experiente em Redes de Computadores e explique os fundamentos de redes de computadores.
Responda seguindo essa estrutura:
Conceito geral
Explicação detalhada
Definição de todos os termos técnicos
Analogia intuitiva
Exemplo prático
Erros comuns de iniciante
Relação com outros conceitos das redes
Resumo em até cinco tópicos
Considere que estou estudando para construir uma base bem sólida em infraestrutura e redes."

"Explique passo a passo tudo o que acontece desde o momento em que um usuário digita um endereço de um site até o carregamento completo da página.
Mostre cada protocolo envolvido.
Em cada etapa descreva: quem envia, quem recebe, qual informação está sendo transmitida e qual problema aquela etapa resolve.
Não pule nenhuma etapa importante."

* Comentários:
O NotebookLM é muito bom para entender o básico de alguns assuntos que você já tenha algumas referências que queira entender, como artigos e sites, mas para aprofundar na área ele dificilmente vai ajudar de verdade a entender diferentes casos de aplicação. Ele tem várias possibilidades de formatos de respostas, como podcasts, vídeos e mapas mentais o que ajuda muito a entender os fundamentos ou as principais ideias do assunto, o que é muito bom. Entretanto, para aprendizado aprofundado na área, é melhor acompanhar materiais mais robustos em teoria como livros e treinar a prática com exercícios reais. Como Inteligência Artificial, ajuda muito a entender referências específicas e as alucinações são bem menores, mas depois de eu testar os mesmos prompts nas ferramentas de IA Claude, Perplexity e o ChatGPT, parecia que as respostas obtidas no NotebookLM foram bem menores e simplificadas mesmo com materiais de teoria bem específicos em comparação com as outras.

Link para acessar o caderno temático: https://notebooklm.google.com/notebook/0f01b63f-be6c-4b0d-8a90-e9a7801b787c

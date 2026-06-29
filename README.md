# mapa-geral-de-redes-notebookLM
Conceitualização de redes na TIC e processos envolvidos a partir de fontes digitais e uso guiado do NotebookLM.

# Introdução e Objetivos
A ideia deste projeto foi basicamente criar um caderno temático para estudos utilizando a ferramenta de IA NotebookLM do Google, onde é possível organizar diferentes fontes selecionadas como banco de dados para o seu projeto e todas as respostas (que podem estar em vários formatos) vão ser baseadas nessas fontes, o que pode ajudar a reduzir alucinações e direcionar o assunto.
O tema escolhido foi redes, protocolos e arquitetura e o objetivo é introduzir e criar uma base sobre os processos e conceitos principais envolvidos na criação e configuração dessas redes.

# Fontes Utilizadas
Tentei usar 4 fontes renomadas e detalhadas do Google Acadêmico e 1 de um site de conceitulização para garantir uma base confiável.
[aula7.pdf](https://github.com/user-attachments/files/29467371/aula7.pdf)
[v9n3art2.pdf](https://github.com/user-attachments/files/29467365/v9n3art2.pdf)
[TL03 2000 ERI Monteiro.pdf](https://github.com/user-attachments/files/29467353/TL03.2000.ERI.Monteiro.pdf)
[Redes_de_Computadores_e_Internet.pdf](https://github.com/user-attachments/files/29467347/Redes_de_Computadores_e_Internet.pdf)
https://www.opservices.com.br/protocolos-de-rede/

# Prompts
Enviei 3 prompts diferentes, um mais específico do que o outro, abordando diferentes camadas de redes.

1. "Explique o funcionamento das redes de computadores diferenciando seus tipos e topologias, do mais simples ao mais avançado. Apresente em formato de tópicos de maneira acessível e detalhada."
A resposta gerada foi bem simples, abordando os tópicos de Escala, Forma de Conexão, Comutação, Organização em Camadas e Protocolos e Estrutura Avançada. Cada tópico usou de 2 a 4 subtópicos explicados em frases.

2. "Simulando um técnico experiente em redes, explique detalhadamente os conceitos necessários para a criação e configuração de uma rede, abordando como saber escolher e interconectar as diferentes camadas  utilizadas na integração de redes. Após explicar a teoria, monte um passo a passo descritivo em formato de tópicos explicando como realizar esse processo na prática, em ambientes avançados ou domésticos."
Aqui além da instrução eu já coloquei um contexto, critérios e o formato de saída, mas a resposta se manteve em um padrão parecido. A parte teórica foi uma explicação simples do Modelo TCP/IP e Encapsulamento, enquanto a prática foram 6 passos bem generalistas e que não especificaram os critérios.

3. "Tendo como ponto de partida que está explicando para uma pessoa inexperiente, responda como se fosse um professor renomado e experiente na área de TIC e redes os principais tipos de protocolos, como é feita sua configuração e a relação de cada um com o modelo OSI. Apresente também como é feita sua configuração de forma detalhada, ilustrando termos importantes e insights necessários para a compreensão. Desenvolva em formato de tópicos com uma síntese ao final."
O resultado foi mais detalhado e explicativo, abordando os tópicos de O Modelo OSI: O Mapa da Comunicação, Principais Tipos de Protocolos,  Como é feita a Configuração, Termos Importamtes e Insights e Síntese. Deu uma base mais sólida, mas decidi tentar adicionar maior detalhamento e os elemento de Cadeia de Pensamento para extrair o melhor resultado porque achei que ficou um pouco redundante.
Ficou assim: "Tendo como ponto de partida que está explicando para um estudante inexperiente, responda como se fosse um professor renomado e experiente na área de TIC e redes os principais tipos de protocolos de rede, como é feita sua configuração e a relação de cada um com o modelo OSI. Apresente também como é feita sua programação de forma detalhada e por quais protocolos de gerência, ilustrando termos importantes e insights necessários para a compreensão. Explicite a cadeia de pensamento necessária para um técnico de TIC e redes ao configurar uma rede profissional em um diagnóstico de rede, com foco na detecção de problemas. Desenvolva em formato longo e completo de tópicos com uma síntese em texto ao final."
Tive de especificar bem mais os componentes do prompt, mas acabou que o resultado ficou simplificado, mas melhor direcionado.

# Resumo Próprio do Assunto
A Tecnologia da Informação e Comunicação é um termo mais geral que descreve todos os recursos utilizados não só para armazenar, mas também transportar informações entre dispositivos, onde a parte de redes é a responsável por transferir esses dados.
Uma rede pode ser classificada por sua extensão, sendo a LAN (Local Area Network) para salas ou prédios e a WANWAN (Wide Area Network) se extendo globalmente, como a própria internet. O wi-fi no geral é uma LAN do tipo WLAN, o que significa que ele pode se propagar sem fios com determinados dispositivos. Também podem ser classificadas quanto à sua topologia, que é como os dispositivos estão conectados fisica ou logicamente, como a em Estrela onde os dispositivos estão conectados a um roteador principal e a Topologia em Malha (Mesh), que tem mais conexões entre dispositivos e é muito mais avançada. O modo de funcionamento é conhecido como Comutação, que hoje em dia o mais comum é a Comutação por Pacotes, onde basicamente os dados requeridos são divididos e podem percorrer diferentes meios para chegar ao destino.
Para que essa comunicação aconteça, são usadas os protocolos, que são meios com regras específicas de como esse transporte de informações ocorre.

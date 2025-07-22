# Projeto-Mousinho-da-Silveira
Análise do desempenho de estudantes

Este projeto tem como objetivo analisar o desempenho de estudantes na matéria de Matemática e Português, focando em como alguns fatores sociais e demográficos podem influenciar suas notas e o número de reprovações. A base de dados utilizada contém informações de alunos das escolas Mousinho da Silveira e Gabriel Pereira, localizadas na região do Alentejo, em Portugal.

Assim como em vários outros países (por exemplo, França ou Venezuela), uma escala de classificação de 20 pontos é usada, onde 0 é a nota mais baixa e 20 é a nota perfeita. Durante o ano letivo, os alunos são avaliados em três períodos, e a última avaliação (nota3) corresponde à nota final.

Este estudo irá considerar dados coletados durante o período de 2005–2006, referentes a duas escolas públicas.

Para esta análise, observamos inicialmente que os dados apresentam valores que parecem destoar dos demais nas notas (nota1, nota2 e nota3). Para garantir a qualidade da nossa análise, iremos trabalhar com o ajuste desses valores através da aplicação de filtros nos dados.

As principais colunas que utilizaremos para responder às nossas perguntas de pesquisa são:

Notas: nota1, nota2, nota3 (Notas dos três períodos)

Reprovações: estudante_nr_reprovacoes (Número de reprovações anteriores)

Status dos Pais: estudante_status_pais (Pais Casados, Pais Divorciados)

Acesso à Internet: estudante_acesso_internet ('yes' ou 'no')

Tamanho da Família: estudante_tamanho_familia (maior_que_3_pessoas, menor_que_3_pessoas)

Sexo: estudante_sexo ('F' para feminino, 'M' para masculino)

Relacionamento amoroso: estudante_relacionamento ('yes' ou 'no')

Ao relacionar as notas dos estudantes com estas variáveis, buscamos identificar possíveis padrões e insights sobre os fatores que podem estar associados ao sucesso ou às dificuldades acadêmicas.

Vamos utilizar as bibliotecas Pandas, Matplotlib e Seaborn para análise e visualização dos dados.

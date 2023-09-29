# dda-lib-ia-EY-Aplicacao_Modelo_de_Representatividade_e_Sentimento
Criado por: lucas.martinsleal@br.ey.com
Atualizado por: lucas.martinsleal@br.ey.com
Data da última atualização: 29/09/2023

## 1-   Descrição
O aplicativo permite que as empresas gerenciem seus indicadores de diversidade baseado em suas mídias sociais.

## 2-   Funcionalidades
- Login: Garante que somente usuários previamente cadastrados na base sharepoint possam utilizar o aplicativo;
  
- Upload Arquivo: Upload de arquivos com verificacao do formato do arquivo e envio para uma lista do Sharepoint .

- Download Template: Download de Arquivo de template -Arquivo removido na sanitizacao-.
  
- Tela de Transparência: Visualizar todos os registros de postagens com relação a representatividade em redes sociais referentes a empresa logada (Registros previamente cadastrados manualmente).

- Edição de Informações de representatividade: Possibilidade de editar as informações da tabela uma a uma - é necessario possuir um perfil especifico para isso -.

- Utilização de listas com mais de 2000 registros: Lógica criada para permitir que o app trabalhe com listas que possuam mais de 2000 registros sem utilizar nenhum tipo de conector premium.

- Dashboards Power BI: Presença de 3 dashboards diferentes no app que apresentam diferentes informações relacionadas as postagens.                     	 	

## 3-   Pré Requisitos
- N/A.

## 4-   Procedimentos de Importação
1) Realizar o Download do arquivo .zip que possui todos os arquivos referente ao acelerador.

2) Acessar a página de soluções da Power Platform, selecionar importar solução e selecionar o arquivo baixado.

3) Uma vez adicionado ao ambiente escolhido a solução ficara disponivel para utilização da pessoa que importou.

4)Caso deseje compartilhar com outras pessoas, o passo a passo se encontra na documentação fornecida neste repositório.


## 5-   Procedimentos de Utilização
O detalhamento das telas e fluxos utilizados estão descritos na documentação presente no repositório, além disso todas as lógicas necessarias do app possuem comentarios para viabilizar a utilização do mesmo.

OBS: O aplicativo está utilizando collections para todas as ações pois não foi incorporada a solução listas sharepoint, procedimento esse que pode ser adotado.
OBS2: Todos os fluxos estão comentados no app pois os fluxos possuem comandos de interação com o Sharepoint e o mesmo não foi incorporado no acelerador

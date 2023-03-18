# MyApplication5

O intuito é desenvolver um aplicativo nativo Android (kotlin), a aplicação deverá interagir com o banco de dados via requisições, 
onde será possivel ler, adicionar, excluir e atualizar dados de um dispositivo como também lstar os dispositivos salvos no servidor para apresenta-los ao usuário da aplicação,
além disso haverá a possibilidade de salva-lo como favorito.

O protótipo conta com a primeira tela sendo a dashboard, a qual apresenta na parte superior um componente de pesquisa de dispositivo,
pesquisando pelo nome do dispositivo, logo abaixo serão mostrados cards para cada dispositivo,
e na parte inferior uma bootoom menu que permite escolher o filtro de que dispositivos mostrar e também um float action buttom (FAB),
a qual permite a adição de novos dispositivos.

Cada card de dispositivo terá no canto esquerdo um icone kebak que permite abrir o menu suspenso deste card. 
O menu flutuante possui quarto itens de acesso: Editar o dispositvo", "informações", "Marcar Favorito"  / "Desmarcar Favorito" e "Remover Dispositivo".

Já a bottom menu além do FAB terá quatro icones, sendo o primeiro a qual irá listar todos os dispositivos adicionados, 
o segundo apenas os dispositivos que foram marcados como favoritos, já o terceiro e quarto serão um filtro dos dispositivos que foram marcados como favoritos,
já o terceiro e quarto serão um filtro dos dispositivos por tipo. Tela "Adicionar dispositivo" / Editar dispositivo",
são telas exatamente iguais em seus componentes, sua diferença é que no primeiro o usuário irá precisar digitar os dados para salvar no servdor,
no segundo ele já possui os dados, mas pode edita-los/atualiza-los.

Já a tela informações, irá listar alguns dos dados dos dspositivos.



Segue a lista de telas e suas obrigatoriedades em faze-las:
-- Lista de dispositivos (dashboard) - Mandatório;
--Tela informações - Mandatório;
--Tela adição (vídeo e/ou alarme) - Opcional;
-----Deverá salvar apenas em banco de dados local
--Search - Opcional;
--Bottom menu (layout): Mandatório
----Itens funcionando (home, bookmark, alarm, video e FAB), Entrega condicionada as telas entregues.
--Desing System Material You - Mandatório;
----Condicionado as telas entregues.


Comunicação com Backend
--Ler os dispositivos e informações - Mandatório;
--Criar/adcionar novos dispositivos - Opcional;
--Atualizar informações de dispositivos já cadastrados - Opcional.
--Deletar/apagar dispositivos - Opcional;
--Response - Tratar com um Toast ao usuário - Opcional.


Hospedagem e gerência de código-fonte:
--Utilizar plataforma de versionamento de código - Mandatório;
----BitBucket, GitHub e o GitLab por exemplo.

Diferencial:
--Programação assíncrona: Exemplo RXJava, Coroutines...
--Clareza na organização de componentes utilizados para construir a tela;
--Preocupação com a UI/UX da aplicação;
--Teste automatizado de alguma das funções desenvolvidas;
--Criar commits frequentes com descrição/resumo;
--Utilizar commits semânticos.


Ferramenta/divas sugeridas:
--Utilização padrão da arquitetura do Android (MVVM);
--Se preocupar primeiro com a lógica da aplicação e depois com o visual.


Contextualização:
--A API trata-se de CRUD (Create, Read, Update e Delete) de dispositivos de vídeo e alarme;
--Dispositivos de vídeo: são os equipamentos que permitem serem acessados para o monitoramento externo de câmeras de segurança;
--Dispositivo de alarme: são os equipamentos que permitem serem adessados para o monitoramento externo e controle de centrais de alarme.

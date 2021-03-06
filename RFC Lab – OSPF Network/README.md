CENÁRIO:
Você possui um pequeno WISP em sua cidade com cerca de 200 assinantes. Até agora, você tem usado o roteamento estático em todos os seus dispositivos de backbone. Você cresceu o suficiente para aproveitar as vantagens do OSPF para a criação automática de rotas. Isso permitirá que você adicione novos pop's, torres ou modifique os existentes sem ter que modificar as rotas estáticas em cada dispositivo sempre que houver uma alteração.
Este laboratório se concentrará em colocar o OSPF em operação pela primeira vez. Embora este laboratório esteja muito próximo de como uma rede de produção seria configurada, ele não deve ser implementado exatamente dessa forma porque alguns dos “ajustes finos” que estão envolvidos nas redes OSPF do mundo real não serão apresentados até os laboratórios posteriores.
Este laboratório se destina a ser construído com roteadores MikroTik usando cabos Ethernet para simular links sem fio em ponte de forma transparente entre torres.
(Recomendo o uso do EVE-NG)

META:
Quando este laboratório for concluído, todas as rotas necessárias para se comunicar com todos os dispositivos deverão ter preenchido a tabela de roteamento de cada roteador. Você deve ser capaz de executar ping em cada dispositivo e winbox em cada dispositivo quando estiver tudo pronto. Os seguintes conceitos serão introduzidos:

a) Adicionando redes ao OSPF

b) Redistribuindo rotas conectadas

c) Redistribuindo rotas padrão

d) Loopbacks

e) Filtros de Roteamento

![image](https://user-images.githubusercontent.com/68615506/142449759-7c77f042-ebdb-41aa-89a5-fdbd4927b000.png)


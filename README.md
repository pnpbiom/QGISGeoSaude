# Plugin QGIS - GeoSaude

O *Plugin QGIS - GeoSaude* permite carregar indicadores, disponibilizados na página [GeoSaude](http://www.geosaude.dgs.pt), para um software de geoprocessamento: o QGIS. Para além destes indicadores, que correspondem a dados relacionados com a saúde dos portugueses apresentados em mapas, foram ainda incluídas camadas indicativas da localização de centros de saúde e farmácias em Portugal.

O presente plugin apenas é suportado pela versão 3.0. do QGIS.



## Instalação

Para a sua instalação, em primeiro lugar e após o *download* de todos os ficheiros, é necessário guardar a pasta que os inclui na diretoria Plugin QGIS. De seguida, procede-se à sua compilação e desenvolvimento, através do comando *pb_tool* (que pode ser instalado por `pip install pb_tool`). Por último, a ativação do plugin é feita no QGIS em: *Módulos -> Gerir e Instalar Módulos -> Instalados*.


## Utilização

Após a instalação e ativação do *Plugin QGis - GeoSaude*, para a recorrer às suas funcionalidades, basta pressionar o ícone correspondente que surgiu na barra de ferramentas.
A janela resultante desta ação conterá uma lista com diversos indicadores que correspondem a camadas vetoriais inseridas no mapa de Portugal. Selecionando o indicador pretendido e pressionado *Ok* a respetiva camada será aberta no QGIS.


## Desenvolvimento

O desevolvimento e compilação do plugin foram possíveis recorrendo ao módulo *Plugin Builder*, às funcionalidades da linguagem *Python* e à utilização da plataforma *Qt*.

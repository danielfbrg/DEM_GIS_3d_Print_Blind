# Modelo tátil em Impressão 3D para auxílio de deficientes visuais

Iniciativa para a construção de modelos através de impressão 3D para auxiliar deficientes visuais a interpretar diferentes pontos de interesse.

* Apresenta sistema de leitura em Braille para identificação da localização;

* O projeto tem por referência mapas táteis comumente utilizados e emprega as vantagens que a técnica de impressão 3D apresenta, incluindo a possibilida ser replicado ilimitadamente a um custo bastante reduzido.

<br>

## Desenvolvimento

<br>
 
#### ALOS PALSAR 

Aquisição dos modelos digitais de elevação através do projeto [Alos Palsar](https://search.asf.alaska.edu/ "ASF Data Search"), os dados entregam resolução espacial de 12,5 metros.

[[Especificações Alos Palsar]](https://asf.alaska.edu/data-sets/derived-data-sets/alos-palsar-rtc/alos-palsar-radiometric-terrain-correction/)

<br>

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/alos%20site.png)
_______

#### Classificação dos dados  

Renderização em banda simples falsa-cor para auxiliar na interpretação dos dados utilizando o [QGIS](https://qgis.org/ "QGIS.Org").

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/propriedades_classificacao.png)
_______

#### Pós classificação

Resultado da simbologia utilizando graduação de cores.

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/raster_classificado.png)
_______

#### Pré visualização dos dados

Funcionalidade incorporada ao QGIS a partir da versão 3.0, pode ser acessada através do menu:
<br>
<br>
`Exibir` ‣ `Nova Visualização de mapa 3D` 
<br>
<br>
Permite ao usuário vizualização 3D do mapa em questão, sendo possível realizar uma estimativa do modelo final. 

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/qgis_3d%20view.png)

_______

#### DEMto3D 

[DEMto3D](https://demto3d.com/) é o primeiro **plugin** a unir **GIS** (Sistema de Informação Geográfica) e **Impressão 3D**. Este complemento está disponível para o software [QGIS](https://qgis.org/) e permite a impressão 3D de DEMs (Modelos Digitais de Elevação).

Deve ser instalado em: 
<br>
<br>
`Complementos` ‣ `Gerenciar e Instalar Complementos...`.
<br>
<br>
Maiores informações podem ser encontradas [aqui](https://github.com/jawensi/DEMto3D-QGIS-Plugin "GitHub DEMto3D-QGIS-Plugin").

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/dem_to3D.png)
_______

#### Área de interesse 

Após selecionar a área de interesse, preencher os demais campos. Atenção ao definir o exagero vertical, cada projeto apresenta suas particularidades e estas devem ser levadas em consideração no momento da configuração.

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/plugin.png)
_______

#### Preparação dos dados em Braile 

Para adicionar o sistema de linguagem Braile utiliza-se a aplicação web, **Gerador de palacas Braille para impressão 3D**, disponibilizada [aqui](https://www.poalab.net.br/t2b/).

Com o gerador é possível inserir o texto desejado e ter como retorno o modelo em formato **.STL** ou **.X3D**, além de permitir pequenas configurações. 

O modelo é tradução do projeto [Text to 3d printable Braille](http://v01pe.github.io/Text2Braille3d/).

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/site_braile.png)
_______

#### Modelo pronto para Impressão 

Ao finalizar a área de interesse e seu rótulo, utilizam-se ferramentas de modelagem 3D para unir as peças que serão impressas. Existem inúmeras ferramentas que podem ser empregadas para esta função como: [Blender](https://www.blender.org/) e [3D Builder](https://www.microsoft.com/pt-br/p/3d-builder/9wzdncrfj3t6#activetab=pivot:overviewtab), ambos softwares gratuitos.

##### Apa do Arquipélago de Santana [[Download do Modelo em .STL](https://# "Em breve")]

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/ilha%20santana%20braile%20model%20pronto.png)

<br>

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/foto_Kana_Manhaes.png)
> Foto: [Kaná Manhães](https://www.odebateon.com.br/site/noticia/impressao/38649/feriados-prolongados-prejudicam-empresas-mas-alavancam-turismo)

<br>

## Outros modelos

##### Ilha Grande [[Download do Modelo em .STL](https://# "Em breve")]

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/ilha.png)

<br>

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/ilha_g.png)
> Foto: [Flickr](https://www.flickr.com/photos/faber_1979/2436568769)

<br>

##### Morro São João [[Download do Modelo em .STL](https://# "Em breve")]

![](https://github.com/danielfbrg/DEM_GIS_3d_Print_Blind/blob/master/img/morro_bsj.png)

<br>

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/morro_.png)
> Foto: [Patricia Kovacs](http://patkovacs.blogspot.com/2012/01/lugares-barra-de-sao-joao.html)

<br>

##### Pãp de Açúcar [[Download do Modelo em .STL](https://# "Em breve")]

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/pao.png)

<br>

![](https://raw.githubusercontent.com/danielfbrg/DEM_GIS_3d_Print_Blind/master/img/vista_p.jpg)
> Foto: [Ccarelo](https://commons.wikimedia.org/wiki/File:Vista_do_Morro_Dona_Marta.jpg)

<br>

<br>

## Fontes

**3D Builder** 
https://www.microsoft.com/pt-br/p/3d-builder/9wzdncrfj3t6?activetab=pivot:overviewtab

**Alos Palsar**
https://search.asf.alaska.edu/

**Blender**
https://www.blender.org/

**DEMto3D**
https://demto3d.com/

**Qgis**
https://qgis.org/en/site/

**Text to 3d printable Braille**
http://v01pe.github.io/Text2Braille3d/

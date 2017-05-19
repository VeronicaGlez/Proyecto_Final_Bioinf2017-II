#README

Este repositorio contiene el trabajo final del curso **"Introducción a la bioinformática e investigación reproducible para análisis genéticos"**. 

En este proyecto se utilizan 12,913 Snps, de pajáro bobo patas azules (Sula nebouxii), para determinar los índices de diversidad genética, posible estructura poblacional y SNPs candidatos a selección, para distintas categorías de edad, en la población de Isla Isabel, México.

Este repositorio está dividido en 4 carpetas principales:

- **bin**: Contiene los scripts utilizados para correr los programas (enumerados con el orden en que se utilizan) para el análisis de datos.

	**<span style="color:blue">1.Análisis exploratorios</span>** 
	
	Script_SNPRelate.sh : Para realizar PCA en R
	
	**<span style="color:blue">2.Análisis de diversidad genética</span>** 
	
	script_hierfstats.sh, script vcftools.sh, script_adegenet.sh
	
	**<span style="color:blue">3.Estructura</span>**
	
	Script_fastStructure.sh, script_Admixture.sh
	

	
	
	**<span style="color:blue">4.Buscando SNPs candidatos</span>**
	
	script_bayescan.sh
	
			
- **data**: Contiene los archivos para correr cada análisis según el programa a utilizar, e.g. incluye archivos .vcf,.012, .txt, etc.
 (algunos pendientes)




- **output**: En esta carpeta se encuentran los archivos de salida para cada script dividos en carpetas.

	-**<span style="color:grey ">Análisis exploratorios</span>**

	
	-**<span style="color:grey">Análisis de diversidad genética</span>**	
	
	-**<span style="color:grey">FastStructure</span>**
	
	-**<span style="color:grey">Admixture</span>**
	
	
	-**<span style="color:grey">SNPs candidatos</span>**




- **FIGURAS**: Contiene las figuras y/o gráficas creadas por R, e.g PCA, Boxplot y Bayescan.





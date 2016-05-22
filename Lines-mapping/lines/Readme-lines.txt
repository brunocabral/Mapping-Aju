## Guidelines para mapear uma linha de onibus ##

1. O mapeamento deve ser feito usando através do Geojson.io usando a ferramenta linha (draw a polyline). 
2. Cada linha de ônibus tem 2 sentidos (ida e volta), portanto deve ser mapeado um conjuntos independente de polylines para cada sentido.
3. Para facilitar a visualização, cada conjunto deve ter a stroke com cores contrastantes (Ex.: Azul para um sentido e Vermelho para o outro)
4. Para ajudar a mapear, utilizar o itinerário disponível no site da SMTT como referência (http://www.smttaju.com.br/smtt/transporte/itinerario-e-horario-dos-onibus)
	4.1 Em caso de dúvida do itinerário, recomendo utilizar como suporte outras ferramentas como Street View por exemplo.
5. Atributos adicionais para adicionar no geojson
	5.1 bus-line: numero da linha
	5.2 bus-direction: sentido da linha (Primeiro ponto/último ponto). 
		Ex: 009- Terminal Marcos Freire / Atalaia
		 então bus-direction: terminalMarcosFreire-atalaia (identação lowerCamelCase)
		 e o mesmo para o sentido oposto bus-direction: atalaia-terminalMarcosFreire
	5.3 bus-way: sentido da linha (0 ou 1)
6. Finalizando o mapeamento. Save > GeoJSON, o nome do arquivo segue o formato \lines\"numerodalinha".geojson. Ex lines\031.geojson
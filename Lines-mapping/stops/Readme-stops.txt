## Guidelines para mapear um ponto de �nibus ##

O mapeamento deste ainda n�o est� sendo realizado da melhor maneira pois est� tudo sobre o mesmo arquivo...

1. Abrir o arquivo stops.geojson na ferramente GeoJson.io
2. Adicionar a localiza��o do ponto de �nibus no mapa utilizando a ferramenta "Draw a marker"
3. Se tiver informa��es adicionais sobre o ponto:
	3.1 Sabe o nome do ponto(ou � terminal)?
		Add row > bus-stop:"nomeDoPonto"
	3.2 Significado das cores (strokes)
		3.2.1 - Vermelho: � terminal de integra��o
		3.2.2 - Verde: Novos pontos instalados pela prefeitura que possuem identifica��o por nome
		3.2.3 - Bege: Novos pontos instalados pela prefeitura mas que N�O tem identifica��o por nome
	
4. Finalizado o mapeamento, Save > GeoJson > salvar como "stops.geojson" em \stops
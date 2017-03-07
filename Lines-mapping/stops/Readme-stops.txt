## Guidelines para mapear um ponto de ônibus ##

O mapeamento deste ainda não está sendo realizado da melhor maneira pois está tudo sobre o mesmo arquivo...

1. Abrir o arquivo stops.geojson na ferramente GeoJson.io
2. Adicionar a localização do ponto de ônibus no mapa utilizando a ferramenta "Draw a marker"
3. Se tiver informações adicionais sobre o ponto:
	3.1 Sabe o nome do ponto(ou é terminal)?
		Add row > bus-stop:"nomeDoPonto"
	3.2 Significado das cores (strokes)
		3.2.1 - Vermelho: É terminal de integração
		3.2.2 - Verde: Novos pontos instalados pela prefeitura que possuem identificação por nome
		3.2.3 - Bege: Novos pontos instalados pela prefeitura mas que NÃO tem identificação por nome
	
4. Finalizado o mapeamento, Save > GeoJson > salvar como "stops.geojson" em \stops
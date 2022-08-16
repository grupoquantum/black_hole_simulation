<div align="justify">
<h3>Black Hole Simulation (Simulação de Buracos Negros)</h3>
<p align=”justify”>
Um <b>Buraco Negro</b> é uma região do espaço-tempo onde o campo gravitacional é tão intenso que nada que atinja o limite do seu horizonte de eventos pode escapar, isso inclui corpos visíveis, partículas atômicas e subatômicas e até mesmo radiações eletromagnéticas como a luz. Segundo a Teoria da Relatividade Geral de Albert Einstein, um corpo massivo suficientemente denso poderá colapsar para dentro de si mesmo vítima da sua própria gravidade e deformar o tecido do espaço-tempo a sua volta para além dos limites gravitacionais conhecidos. A distorção gravitacional incidente sobre o tecido do espaço-tempo gera aberrações na passagem do tempo fazendo com que ele passe de forma diferente aos arredores do buraco negro com relação a pontos distantes da sua localização.
</p>
<div align="center"><img src="https://github.com/aiquantumneuro/black_hole_simulation/blob/main/black_hole.jpg"></div>
<p align=”justify”>
<b>Como surgem os Buracos Negros?</b> Buracos Negros podem surgir no final da vida de estrelas supermassivas com a partir de cerca de 10 vezes a massa do Sol. A transformação ocorre quando essa estrela explode por excesso de matéria e falta de combustível dando origem ao que conhecemos como Supernova ou através de uma explosão de raios gamma. A estrela colapsa quando começa a fundir elementos mais leves em elementos mais pesados como carbono e ferro que passam a torná-la cada vez mais densa até que ela chegue a um ponto de densidade máxima.
</p>
<p align=”justify”>
<b>Singularidade:</b> A Singularidade é o centro de massa do buraco negro onde se encontra o ponto exato de localização da estrela colapsada, nesse ponto a gravidade tende ao infinito e as leis da Física que conhecemos não se aplicam. A região que envolve a singularidade é conhecida como <u>corpo negro</u> pois apenas absorve luz e não a emite, daí o nome buraco negro.
</p>
<p align=”justify”>
<b>Poço Gravitacional:</b> O Poço Gravitacional é a cavidade formada em decorrência da pressão exercida do buraco negro sobre o tecido do espaço-tempo fazendo com que esse tecido se curve para comportar a massa que incide sobre ele.
</p>
<p align=”justify”>
<b>Horizonte de Eventos:</b> O Horizonte de Eventos é a região interna do poço gravitacional de um buraco negro da qual se é impossível escapar. O escape é impossível por que a atração gravitacional de um buraco negro tende ao infinito, em decorrência disso a velocidade para que um corpo escape dessa atração também deveria tender ao infinito, porém de acordo com os leis da Física  nada pode ser mais rápido que a luz fazendo com que nem mesmo a luz tenha velocidade de escape o suficiente para escapar. Nessa região as leis da Física que conhecemos não se aplicam e a Matemática se torna incoerente sendo este um dos principais limites do conhecimento humano. Quanto mais próximo do horizonte de eventos mais devagar o tempo passa para o observador próximo a ele e mais rápido para o observador que esteja distante dele. Isso quer dizer que se em uma situação hipotética um viajante da Terra ficar por poucas horas próximo o suficiente do horizonte de eventos quando este retornar para a Terra já terão se passado dezenas, centenas ou até milhares de anos no planeta de origem enquanto que para este viajante passaram-se apenas algumas horas. Enquanto que o viajante estaria apenas algumas horas mais velho as pessoas que aqui ficaram poderão já ter morrido de velhice. Essa passagem distorcida do tempo é sempre proporcional a distância de proximidade com o horizonte de eventos, quanto mais próximo dele maior será a distorção temporal. Essa é uma das maneiras matematicamente possíveis de se viajar no tempo para o futuro ainda que a viagem para o passado não seja Fisicamente possível uma vez que os efeitos dessa distorção são irreversíveis.
</p>
<p align=”justify”>
<b>Lente Gravitacional:</b> A Lente Gravitacional é um efeito que ocorre quando a luz passa pelos entornos do horizonte de eventos e é defletida de modo a se curvar pelas laterais e causar um efeito de lente amplificadora para quem observa. A distorção é semelhante ao que acontece quando se olha por através de uma lente de vidro a partir de um ponto distante dela.
</p>
<p align=”justify”>
<b>Radiação Hawking:</b> A Radiação Hawking é uma teoria proposta pelo Físico Britânico Stephen Hawking que formulou suas equações a partir da observação de fenômenos quânticos onde partículas surgem espontaneamente com suas respectivas antipartículas por meio de flutuações no vácuo quântico se aniquilando instantaneamente por possuírem cargas opostas. Com isso Hawking chegou ao pressuposto de que quando este fenômeno ocorre nos limites do horizonte de eventos a partícula voltada para a extremidade externa do buraco negro escapa em forma de radiação enquanto que a sua respectiva contraparte é sugada pela força gravitacional do buraco negro.
</p>
<p align=”justify”>
<b>Disco de Acreção:</b> O Disco de Acreção de um buraco negro é a circunferência de detritos de matéria que circundam o horizonte de eventos atraídos pela força gravitacional do mesmo. Esses detritos são acrescidos a matéria do corpo negro de um buraco negro aumentando gradativamente a sua densidade. Esse disco de detritos devido a alta velocidade de colisão entre estes restos de matéria poderá se tornar incandescente fazendo com que possa ser visto a olho nu em distâncias suficientemente próximas. Dizemos que um buraco negro acreta quando este absorve matéria ao seu redor.
</p>
<p align=”justify”>
<b>Gradiente Gravitacional:</b> Quanto mais próximo do centro de massa do buraco negro maior será a força de atração gravitacional, logo de maneira proporcionalmente oposta quanto mais distante do mesmo menor será a influencia gravitacional exercida pelo buraco negro. A este efeito gravitacional gradativo damos o nome de Gradiente ou Gradiente Gravitacional.
</p>
<br>
<pre>
	<code>
from Neuraline.ComputationalPhysics.black_hole_simulation import BlackHoleSimulation # importa o algoritmo de Simulação de Buracos Negros do módulo de Física Computacional
BLACK_HOLE_BLACK_BODY_ACCRETION_LEVEL = 1.0 # nível de acreção do corpo negro em graus percentuais de 0 (0%) a 1 (100%).
BLACK_HOLE_SPACE_TEMPERATURE_LEVEL = 0.0 # nível da temperatura espacial em relação ao buraco negro de 0 (0%) a 1 (100%).
BLACK_HOLE_BLACK_BODY_EXTERNAL_TEMPERATURE = 60.0 # temperatura externa do corpo negro em nanokelvins.
VISIBLE_LIGHT_SPECTRUM = 370.0 # espectro da luz visível emitida pela acreção de matéria em nanômetros.
BLACK_HOLE_ACCRETION_RADIUS = 1.5 # medida do raio de acreção em radianos.
BLACK_HOLE_ACCRETION_WIDTH = 10.0 # largura de expansão da acreção do buraco negro em dias-luz.
BLACK_HOLE_ACCRETION_GLOW_LEVEL = 0.9 # nível do brilho total causado pela acreção em graus percentuais de 0 (0%) a 1 (100%).
BLACK_HOLE_ACCRETION_TEMPERATURE = 1000000.0 # temperatura de acreção do buraco negro em kelvins.
STARS_GLOW_LEVEL = 1.0 # nível do brilho das estrelas no campo de visão em graus percentuais de 0 (0%) a 1 (100%).
GALAXY_GLOW_LEVEL = 0.4 # nível do brilho da galáxia no campo de visão em graus percentuais de 0 (0%) a 1 (100%).
LEVEL_OF_PLANETARY_ENVIRONMENTAL_IMPACT = 0.1 # nível de brilho do orbital (lua/planeta) causado pelo impacto ambiental no campo de visão em percentuais de 0 (0%) a 1 (100%).
PLANETARY_LUMINOSITY_LEVEL = 1.5 # nível de luminosidade orbital/planetária em graus percentuais de 0 (0%) a 1 (100%).
BLACK_HOLE_N_STEPS = 100 # número de quadros de uma simulação matemática para outra.
BLACK_HOLE_QUALITY = 'medium' # qualidade da simulação, poderá ser medium (qualidade média com processamento médio), fast (qualidade baixa com processamento rápido), high (qualidade alta com processamento lento e alta demanda por hardware).
BLACK_HOLE_ACCRETION_DISK = True # se True, exibirá o disco de acreção, se False, colocará o disco de acreção fora do espectro da luz visível.
PLANET_ENABLED = False # se True, exibirá um orbital (planeta genérico) orbitando o buraco negro, se False, não exibirá o orbital/planeta.
PLANET_DISTANCE = 7.0 # distância do orbital/planeta em relação ao buraco negro em dias-luz.
PLANET_RADIUS = 0.4 # medida do orbital/planeta em radianos.
BLACK_HOLE_LORENTZ_CONTRACTION = True # se True, usará o cálculo da contração de Lorentz-FitzGerald, se False, irá ignorar a contração de Lorentz-FitzGerald.
BLACK_HOLE_GRAVITATIONAL_TIME_DILATION = True # se True, usará o cálculo da dilatação gravitacional do tempo, se False, irá ignorar o cálculo da dilatação do tempo.
BLACK_HOLE_ABERRATION = True # se True, habilitará o fenômeno de aberração, se False, irá ignorar o cálculo de aberração.
BLACK_HOLE_BEAMATION = True # se True, permitirá a transmissão de informação e energia, se False, irá ignorar o cálculo de transmissão.
BLACK_HOLE_DOPPLER_SHIFT = True # se True, usará o cálculo do efeito de deslocamento Doppler, se False, irá ignorar o deslocamento Doppler.
BLACK_HOLE_LIGHT_TRAVEL_TIME = True # se True, usará o cálculo do deslocamento da luz, se False, irá ignorar o cálculo do deslocamento da luz.
BLACK_HOLE_TIME_SCALE = 1.0 # escala temporal do horizonte de eventos em relação ao observador em graus percentuais de 0 (0%) a 1 (100%).
OBSERVER_MOTION = True # se True, habilitará o movimento do observador, se False, irá ignorar o movimento do observador.
OBSERVER_DISTANCE = 11.0 # distância do observador em relação ao disco de acreção na escala de dias-luz.
OBSERVER_ORBITAL_INCLINATION = -10.0 # grau de inclinação orbital do observador.
black_hole = BlackHoleSimulation( # executa a simulação do Buraco Negro através dos cálculos de Astrofísica habilitados ou desabilitados acima.
	BLACK_HOLE_BLACK_BODY_ACCRETION_LEVEL=BLACK_HOLE_BLACK_BODY_ACCRETION_LEVEL, # atribuição do nível de acreção do corpo negro.
	BLACK_HOLE_SPACE_TEMPERATURE_LEVEL=BLACK_HOLE_SPACE_TEMPERATURE_LEVEL, # atribuição do nível de temperatura espacial.
	BLACK_HOLE_BLACK_BODY_EXTERNAL_TEMPERATURE=BLACK_HOLE_BLACK_BODY_EXTERNAL_TEMPERATURE, # atribuição da temperatura externa em nanokelvins.
	VISIBLE_LIGHT_SPECTRUM=VISIBLE_LIGHT_SPECTRUM, # atribuição do espectro de luz visível em nanômetros.
	BLACK_HOLE_ACCRETION_RADIUS=BLACK_HOLE_ACCRETION_RADIUS, # atribuição dos radianos da acreção.
	BLACK_HOLE_ACCRETION_WIDTH=BLACK_HOLE_ACCRETION_WIDTH, # atribuição da largura de expansão da acreção em dias-luz.
	BLACK_HOLE_ACCRETION_GLOW_LEVEL=BLACK_HOLE_ACCRETION_GLOW_LEVEL, # atribuição do nível do brilho de acreção.
	BLACK_HOLE_ACCRETION_TEMPERATURE=BLACK_HOLE_ACCRETION_TEMPERATURE, # atribuição da temperatura causada pela acreção em kelvins.
	STARS_GLOW_LEVEL=STARS_GLOW_LEVEL, # atribuição do nível de brilho das estrelas.
	GALAXY_GLOW_LEVEL=GALAXY_GLOW_LEVEL, # atribuição do nível de brilho da galáxia.
	LEVEL_OF_PLANETARY_ENVIRONMENTAL_IMPACT=LEVEL_OF_PLANETARY_ENVIRONMENTAL_IMPACT, # atribuição do impacto ambiental no corpo orbital.
	PLANETARY_LUMINOSITY_LEVEL=PLANETARY_LUMINOSITY_LEVEL, # atribuição do nível de luminosidade do corpo orbital.
	BLACK_HOLE_N_STEPS=BLACK_HOLE_N_STEPS, # atribuição do número referente a quantidade de quadros por simulação computacional.
	BLACK_HOLE_QUALITY=BLACK_HOLE_QUALITY, # atribuição da qualidade da simulação computacional.
	BLACK_HOLE_ACCRETION_DISK=BLACK_HOLE_ACCRETION_DISK, # atribuição do estado do disco de acreção.
	PLANET_ENABLED=PLANET_ENABLED, # atribuição do estado do corpo orbital.
	PLANET_DISTANCE=PLANET_DISTANCE, # atribuição da distância do corpo orbital em dias-luz.
	PLANET_RADIUS=PLANET_RADIUS, # atribuição da medida do corpo orbital
	BLACK_HOLE_LORENTZ_CONTRACTION=BLACK_HOLE_LORENTZ_CONTRACTION, # atribuição do estado da contração de Lorentz-FitzGerald.
	BLACK_HOLE_GRAVITATIONAL_TIME_DILATION=BLACK_HOLE_GRAVITATIONAL_TIME_DILATION, # atribuição do estado de dilatação gravitacional do tempo.
	BLACK_HOLE_ABERRATION=BLACK_HOLE_ABERRATION, # atribuição do estado da aberração.
	BLACK_HOLE_BEAMATION=BLACK_HOLE_BEAMATION, # atribuição do estado de transmissão de informação e energia representado por iluminação.
	BLACK_HOLE_DOPPLER_SHIFT=BLACK_HOLE_DOPPLER_SHIFT, # atribuição do estado de deslocamento Doppler.
	BLACK_HOLE_LIGHT_TRAVEL_TIME=BLACK_HOLE_LIGHT_TRAVEL_TIME, # atribuição do estado de viagem da luz no tempo.
	BLACK_HOLE_TIME_SCALE=BLACK_HOLE_TIME_SCALE, # atribuição do nível de escala temporal distorcida pelo poço gravitacional.
	OBSERVER_MOTION=OBSERVER_MOTION, # atribuição do estado de movimentação do observador.
	OBSERVER_DISTANCE=OBSERVER_DISTANCE, # atribuição da distância do observador em dias-luz.
	OBSERVER_ORBITAL_INCLINATION=OBSERVER_ORBITAL_INCLINATION # atribuição do grau de inclinação do observador.
) # parâmetros de inicialização da simulação computacional.
ARTIFICIAL_NEURAL_NETWORK, QUANTUM_SIMULATION = True, False # habilitação dos recursos matemáticos aplicados a simulação
black_hole_result = black_hole.run( # execução da simulação computacional utilizando os cálculos dos parâmetros de inicialização.
	ARTIFICIAL_NEURAL_NETWORK=ARTIFICIAL_NEURAL_NETWORK, # atribuição do estado de utilização de redes neurais artificiais na simulação.
	QUANTUM_SIMULATION=QUANTUM_SIMULATION # atribuição do estado de utilização de cálculos de otimização quântica na simulação.
)# parâmetros de execução da simulação computacional.
print(black_hole_result) # exibição do estado da simulação, se True a simulação terá sido construída com sucesso, caso contrário poderão existir erros de configuração.
	</code>
</pre>
<br>
Resultado:
<pre>
	<code>
True
	</code>
</pre>
<br>
<p align=”justify”>
Confira no código acima a arquitetura de construção da simulação computacional de um buraco negro com a biblioteca de códigos Neuraline. Para essa simulação o algoritmo cuida de aplicar toda a complexidade Física e Matemática das equações necessárias para que você se foque somente na configuração dos parâmetros de visualização. Este algoritmo utiliza cálculos de Astrofísica aliados a simulações quânticas por meio de redes neurais artificiais que poderão ser habilitadas ou desabilitadas através dos parâmetros do método de execução. Você poderá alterar os parâmetros e experimentar os efeitos Físicos dessas alterações na simulação.
</p>
</div>

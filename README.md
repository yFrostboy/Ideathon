# Ideathon
EcoCompare

Problema - Passageiros de transporte público frequentemente perdem o ônibus por erro no cálculo do tempo de caminhada até o ponto, ou aguardam tempo excessivo no local por falta de informação precisa.

Solução - Aplicação web estática que calcula o tempo necessário para o passageiro sair de casa. O usuário informa a linha, o ponto de parada e o tempo de caminhada. A ferramenta exibe o ônibus em movimento no mapa e avisa o momento exato de saída ("Saia em X min" ou "Saia agora!").

Como Rodar - Configure um servidor local, como Apache/Nginx e acesse via localhost.

Nota para desenvolvimento - Adicionar captura ao final da URL permite imprimir coordenadas de latitude e longitude no console ao clicar no mapa.


v Limitações Conhecidas v

  Dados Simulados: Trajetos, posições de ônibus e pontos são fictícios.

  Cálculo Simplificado: Previsão baseada em velocidade média de 25 km/h, sem considerar trânsito real ou paradas.

  Trajeto Circular: O ônibus reinicia o percurso ao atingir o final da linha.

  Conexão Exigida: Requer internet para carregar os recursos do OpenStreetMap e Google Fonts.

  Sem Notificação Push: Funciona apenas com a página aberta no navegador.   

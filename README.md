# Desenvolvimento

## Arquitetura do Sistema

A solução proposta utiliza um ESP32 como dispositivo IoT para rastrear a localização de carrinhos na fábrica da John Deere. 

![Arquitetura do site JDuber](ArquiteturadositeJDuber.jpg)


### Componentes
1. **ESP32**: Responsável por capturar os dados de localização e transmitir ao servidor.
2. **Servidor**: Hospedado na nuvem (ex: AWS, Firebase), responsável por armazenar e processar os dados recebidos.
3. **Frontend**: Interface gráfica onde os dados são exibidos para os usuários, implementado em HTML/CSS/JavaScript.
4. **Plataforma de Integração IoT**: Exemplo, Ubidots ou Firebase, utilizada para gerenciar os dados do ESP32.

### Tecnologias Envolvidas
- **ESP32**: Microcontrolador IoT usado para a coleta de dados.
- **Firebase**: Banco de dados em tempo real e backend para armazenamento.
- **Mapbox**: Usado para visualização de mapas indoor.
- **Hostinger**: Hospedagem do site e integração com o backend.

## Funcionamento

1. O ESP32 coleta dados da plataforma/carrinho usando sensores.
2. Os dados são transmitidos para o servidor utilizando o Wi-Fi interno da fábrica.
3. O servidor processa os dados e atualiza a localização dos carrinhos em tempo real.
4. A interface web exibe a localização e status dos carrinhos.
5. Resultado esperado: um sistema eficiente de rastreamento de plataformas dentro da fábrica.

---

# Resultados

A aplicação desenvolvida é capaz de:
- Monitorar a localização de plataformas de forma precisa e em tempo real.
- Exibir as rotas dos carrinhos na fábrica em um mapa interativo.
- Abaixo estão alguns prints demonstrando o funcionamento da aplicação:

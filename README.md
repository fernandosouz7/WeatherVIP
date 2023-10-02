# WeatherVIP

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

O WeatherVIP é um aplicativo de previsão do tempo que permite aos usuários verificar a previsão do tempo atual e futura de qualquer cidade do mundo. Ele utiliza a API pública OpenWeatherMap para obter informações meteorológicas atualizadas.

## Recursos do Aplicativo

- **Tela de Pesquisa:** Os usuários podem pesquisar cidades pelo nome.
- **Tela de Detalhes:** Após selecionar uma cidade, os usuários podem ver detalhes sobre a previsão do tempo atual, como temperatura, umidade, velocidade do vento, condições climáticas, etc.
- **Previsão de 5 Dias:** Os usuários também podem visualizar a previsão do tempo para os próximos 5 dias.
- **Mapa Interativo:** O aplicativo inclui um mapa interativo que exibe a localização da cidade e as informações meteorológicas.
- **Histórico de Pesquisa:** O aplicativo mantém um histórico das cidades pesquisadas pelos usuários.

## Tecnologias Utilizadas

- Arquitetura VIP-C para a estrutura do aplicativo.
- RxSwift para lógica reativa e fluxos de dados.
- Cartography para criação de layouts programáticos.
- Alamofire para fazer solicitações HTTP à API do OpenWeatherMap.
- Integração com a API pública OpenWeatherMap para dados meteorológicos.

## Como Executar o Projeto

1. Clone este repositório em seu computador:

```bash
git clone (https://github.com/fernandosouz7/WeatherVIP)
```

2. Navegue até o diretório do projeto
```bash
cd WeatherVIP
```

3.  Abra o projeto no Xcode
```bash
open WeatherVIP.xcodeproj
```

## Contribuindo

Contribuições são bem-vindas! Se você gostaria de contribuir para o projeto, siga estas etapas:

1. Faça um fork do repositório.
2. Crie uma nova branch com a sua feature ou correção de bug: `git checkout -b minha-feature`
3. Faça suas alterações e faça commit delas: `git commit -m "Adiciona minha feature"`
4. Envie suas alterações para a sua branch no repositório forkado: `git push origin minha-feature`
5. Abra um pull request para o repositório original.


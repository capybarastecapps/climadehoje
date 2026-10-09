# Política de Privacidade - Clima de Hoje

**Última atualização: 09/10/2026

Esta Política de Privacidade descreve como o aplicativo **Clima de Hoje**, desenvolvido por **capybarastecapps**, coleta, usa, armazena e protege suas informações ao utilizar nosso aplicativo móvel.

---

## 1. Informações que Coletamos e Como as Utilizamos

O **Clima de Hoje** foi projetado para respeitar a sua privacidade. Coletamos apenas as informações estritamente necessárias para fornecer previsões do tempo precisas, mapas, navegação e informações astronômicas.

### a) Dados de Localização (GPS e Redes)
- **O que coletamos:** Dados de localização geográfica em tempo real (latitude e longitude) do seu dispositivo, mediante sua permissão explícita.
- **Para que usamos:** Para fornecer previsões meteorológicas locais atualizadas, índice UV, qualidade do ar (IQA), eventos astronômicos (nascer e pôr do sol/lua) e exibir sua localização atual em mapas.
- **Armazenamento:** A localização não é armazenada em servidores externos mantidos por nós. Ela é processada temporariamente e mantida em cache local no próprio dispositivo por um curto período (até 30 minutos) para otimizar o desempenho do aplicativo e economizar bateria e tráfego de dados.

### b) Dados do Dispositivo e Sensores
- **O que coletamos:** Leituras dos sensores de orientação (bússola / magnetômetro) do seu dispositivo.
- **Para que usamos:** Exclusivamente para a funcionalidade de bússola e direcionamento no aplicativo.
- **Armazenamento:** Os dados dos sensores são processados localmente no dispositivo em tempo real e nunca são transmitidos para servidores externos.

### c) Buscas e Cidades Favoritas (CEP e Nomes de Cidades)
- **O que coletamos:** Nomes de cidades ou CEPs digitados voluntariamente pelo usuário.
- **Para que usamos:** Para buscar informações climáticas relativas à região informada e permitir a gestão de cidades salvas.
- **Armazenamento:** Suas cidades favoritas e preferências de exibição são salvas apenas localmente no seu dispositivo.

---

## 2. Serviços e APIs de Terceiros

Para disponibilizar mapas de alta precisão e dados meteorológicos completos, o aplicativo utiliza serviços de parceiros confiáveis:

1. **OpenWeather API**
   - **Finalidade:** Fornecimento de dados de clima em tempo real, previsões estendidas, índice UV e qualidade do ar.
   - [Política de Privacidade da OpenWeather](https://openweather.co.uk/privacy-policy)

2. **Mapbox**
   - **Finalidade:** Renderização de mapas estilizados em modo escuro e geocodificação reversa (identificação otimizada do nome do bairro e cidade com cache local).
   - [Política de Privacidade da Mapbox](https://www.mapbox.com/legal/privacy)

3. **ViaCEP**
   - **Finalidade:** Consulta e localização automática de municípios brasileiros através do CEP inserido pelo usuário.
   - [Termos do ViaCEP](https://viacep.com.br/)

---

## 3. Armazenamento Local e Cache

O aplicativo utiliza o armazenamento local do dispositivo (`SharedPreferences`) para:
- Salvar suas preferências de unidade de medida (Celsius/Fahrenheit, km/h, mbar).
- Armazenar em cache local os dados climáticos e de localização por até 30 minutos para garantir respostas instantâneas e economizar dados móveis.

Nenhum desses dados é enviado para bancos de dados externos ou terceiros para rastreamento.

---

## 4. Compartilhamento e Segurança dos Dados

- **Não vendemos nem compartilhamos** suas informações pessoais ou dados de localização com anunciantes ou empresas de marketing.
- As requisições de rede feitas para as APIs citadas acima transmitem apenas os dados estritamente necessários para a execução dos serviços (ex: coordenadas geográficas para obter a temperatura do local).

---

## 5. Permissões do Sistema

O aplicativo solicita as seguintes permissões no dispositivo:
- **Localização (`ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`):** Para obter dados climáticos automáticos da sua posição atual.
- **Acesso à Internet (`INTERNET`):** Para carregar atualizações de clima, mapas e eventos astronômicos.

Você pode ativar ou desativar as permissões de localização a qualquer momento nas **Configurações** do seu dispositivo Android/iOS.

---

## 6. Retenção e Exclusão de Dados

Como não exigimos cadastro nem login, **não armazenamos suas informações em servidores**. 

Você pode apagar todas as configurações e caches mantidos pelo aplicativo a qualquer momento limpando os dados do aplicativo nas **Configurações do Sistema > Aplicativos > Clima de Hoje > Armazenamento** ou desinstalando o app.

---

## 7. Contato e Suporte

Se você tiver qualquer dúvida sobre esta Política de Privacidade ou sobre a gestão de dados no **Clima de Hoje**, entre em contato com a equipe de suporte:

- **Desenvolvedor:** capybarastecapps
- **E-mail de suporte:**  capybarastecapps@gmail.com

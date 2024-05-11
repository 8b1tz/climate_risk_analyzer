# Relatório de Riscos e Condições Climáticas Extremas

## Descrição
Este projeto foi desenvolvido como parte do curso de Imersão em Inteligência Artificial da Alura.Ele consiste em um sistema automatizado para a geração de relatórios profissionais sobre riscos e condições climáticas extremas em determinada localidade. O sistema utiliza informações de localização e dados meteorológicos para produzir relatórios personalizados e informativos.

## Funcionalidades
- **Obtenção de Informações de Localização**: Utiliza o endereço IP do usuário para obter informações sobre a localidade, como latitude, longitude e nome da cidade.
- **Coleta de Dados Meteorológicos**: Utiliza as coordenadas geográficas obtidas para buscar dados meteorológicos atualizados da região.
- **Geração Automatizada de Relatórios**: Utiliza um modelo de inteligência artificial generativa para criar relatórios personalizados com base nas informações de localização e dados meteorológicos.
- **Exportação para PDF**: Os relatórios gerados são exportados para formato PDF para facilitar o compartilhamento e a distribuição.

## Tecnologias Utilizadas
- **Python**: Linguagem de programação utilizada para o desenvolvimento do sistema.
- **Requests**: Biblioteca para realizar requisições HTTP e obter informações de localização e dados meteorológicos.
- **FPDF2**: Biblioteca para criar e manipular arquivos PDF.
- **Google GenerativeAI**: Biblioteca para acesso a modelos de inteligência artificial generativa do Google.

## Como Usar
1. Clone o repositório para sua máquina local.
2. Execute os scripts principais `notebook_climate_risk_analyzer.ipynb.py`.
3. O relatório será gerado automaticamente e salvo em formato PDF.



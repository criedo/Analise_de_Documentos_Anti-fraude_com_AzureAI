# Análise de Documentos Anti-Fraude com Azure AI
![Azure AI](https://img.shields.io/badge/Azure%20AI-Powered-blue)
![Python](https://img.shields.io/badge/Python-3.x-yellowgreen)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

Este projeto apresenta uma implementação de uma solução de análise automatizada de documentos utilizando AzureAI para identificar padrões de fraude, validar autenticidade e aumentar a segurança de transações e processos empresariais, garantindo maior confiabilidade no processamento de documentos sensíveis.
É demonstrado como usar os serviços do Azure AI, como **Form Recognizer** e **Computer Vision**, para analisar documentos e identificar possíveis fraudes de maneira eficiente.

## Funcionalidades
- **Extração de Dados Estruturados**: Usando o Azure Form Recognizer para capturar pares de chave-valor de documentos digitalizados.
- **Detecção de Anomalias Visuais**: Identificação de edições ou inconsistências em documentos usando Azure Computer Vision.
- **Escalabilidade**: Preparado para processamento em larga escala utilizando a nuvem Azure.
- **Automação**: Reduz o trabalho manual e acelera a análise de documentos.

## Tecnologias Utilizadas
- **Linguagem**: Python 3.x
- **Serviços do Azure**:
  - Azure Form Recognizer
  - Azure Computer Vision
- **Pacotes Python**:
  - `azure-ai-formrecognizer`
  - `azure-cognitiveservices-vision-computervision`
  - `msrest`

## Instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/mario-evangelista/analise-documentos-anti-fraude.git
   cd analise-documentos-anti-fraude
   ```
2. Crie um ambiente virtual e ative:
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
4. Configure suas chaves e endpoints do Azure nos locais indicados no código.

## Uso
1. Coloque os documentos para análise na pasta do projeto.
2. Execute o script principal:
   ```bash
   python main.py
   ```
3. O script exibirá no terminal os resultados da extração de texto e análise visual.

## Estrutura do Projeto
```plaintext
.
├── main.py                 # Código principal do projeto
├── README.md               # Este arquivo
├── requirements.txt        # Dependências do projeto
└── exemplos/
    ├── exemplo_documento.pdf
    └── exemplo_imagem.png
```

## Recursos utilizados
- [Azure Form Recognizer Documentation](https://learn.microsoft.com/en-us/azure/applied-ai-services/form-recognizer/)
- [Azure Computer Vision Documentation](https://learn.microsoft.com/en-us/azure/cognitive-services/computer-vision/)

## Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.

Agradeço a @mario-evangelista pela inspiração e possibilidade de acessar as informações para analisar e compreender a atividade.

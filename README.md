# Análise Multimodal de Imagens Médicas com MedGemma 

Este repositório contém uma implementação em Python para realizar análises clínicas preliminares e descrições visuais de imagens médicas (como lesões dermatológicas) utilizando o modelo multimodal de IA **MedGemma** (`google/medgemma-4b-it`) via biblioteca `transformers` da Hugging Face.

## Funcionalidades
Pipeline Multimodal: processamento combinado de instruções em texto e imagens via URLs.
Uso de chat templates: implementação alinhada com as melhores práticas de prompts estruturados (`system` e `user`).
Otimização de memória: configuração nativa para carregamento em precisão `bfloat16` e mapeamento dinâmico de dispositivos (`device_map="auto"`).

## Pré-requisitos e acesso ao modelo
O **MedGemma** é um modelo com termos de uso específicos. Antes de rodar o código, você precisa:
1. Criar uma conta no [Hugging Face](https://huggingface.co/).
2. Acessar a página do modelo [google/medgemma-4b-it](https://huggingface.co/google/medgemma-4b-it) e aceitar as condições de licença.
3. Gerar um **Token de Acesso (HF Token)** nas suas configurações de perfil.
4. Lembre-se: As respostas do modelo são geradas por IA e destinam-se a fins de demonstração.

## Instalação e execução

1. **Clone o repositório:**
   ```bash
   git clone [[https://github.com/SEU_USUARIO/medgemma-image-analysis.git](https://github.com/lucassantoslopes/Analise-multimodal-de-imagens-de-saude-MedGemma)]

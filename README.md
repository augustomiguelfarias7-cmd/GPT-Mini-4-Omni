GPT-Mini-4-Omni

Um modelo multimodal que combina linguagem, código, imagens, áudio e vídeo em uma única arquitetura.
Este projeto é inspirado em modelos avançados como GPT, mas implementado de forma simplificada e aberta para estudo.

🚀 Recursos principais

Treinamento Multimodal:

Textos multilíngues da Wikipedia

Base de código (Python, JavaScript, Java, C++, C)

Imagens e vídeos (placeholders e datasets customizáveis)

Áudio como representação vetorial


Geração de Imagens em 12K 🖼️

Implementação de VAE otimizado para geração em alta resolução

Estratégia de blocos (patches de pixels) que são reconstruídos em até 12K


Modelo Transformer Avançado

Blocos de atenção multi-head

Camadas de feed-forward otimizadas

Embeddings para texto e posição


Interação inteligente com usuários

Reconhecimento de sentimentos simples no texto

Respostas adaptadas e recomendações



⚙️ Como funciona

1. O texto e código são tokenizados e processados pelo Transformer.


2. Imagens passam pelo ImageVAE, sendo comprimidas e reconstruídas.


3. Vídeos são tratados como sequência de frames de imagens.


4. Áudio é convertido em embeddings vetoriais.


5. O modelo pode gerar texto, reconstruir imagens em 12K e integrar diferentes modalidades.



🛠️ Tecnologias usadas

PyTorch

HuggingFace Datasets

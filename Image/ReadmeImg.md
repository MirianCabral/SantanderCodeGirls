# Pasta contendo Imagens sobre os projetos

### Imagem.png
- Fluxo de dados
1. O usuário envia um arquivo -> Armazenado no S3 Bucket
2. O S3 dispara um evento que ativa o Lambda Function.
3. A Lambda Verifica:
   - Se for um processamento simples -> Processa e grava direto no S3 Bucket
   - Se for um processamento pesado -> Envia o arquivo para o EC2
4. A EC2 processa o arquivo
   - Usa EBS para armazenamento temporário
   - Gera um resultado final e salva no S3
5. O usuário ou o sistema acessa os resultados no S3

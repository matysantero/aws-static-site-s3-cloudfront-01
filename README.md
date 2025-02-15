﻿# aws-static-site-s3-cloudfront
# Site Estático Hospedado na AWS com S3 e CloudFront

## 📚 Sobre o Projeto
Este projeto demonstra como criar e hospedar um site estático utilizando os serviços da AWS. Ele inclui o uso do **S3** para armazenamento, **CloudFront** para distribuição global e **Route 53** para configurar um domínio personalizado.

### 🎯 Objetivos
- Criar e configurar um bucket S3 para hospedagem estática.
- Configurar o CloudFront para distribuição global com HTTPS.
- Integrar um domínio personalizado usando o Route 53.

---

## 🚀 Tecnologias Utilizadas
- **AWS S3**: Armazenamento de objetos para o site.
- **AWS CloudFront**: Distribuição global com baixa latência.
- **AWS Route 53**: Configuração de DNS e domínio personalizado.
- **HTML/CSS**: Para criar o site estático.

---

## 📂 Estrutura do Repositório
```plaintext
/
├── site/               # Arquivos do site estático
│   ├── index.html      # Página inicial
│   ├── style.css       # Estilos
│   └── assets/         # Imagens e outros recursos
├── screenshots/        # Capturas de tela do site e configurações
├── README.md           # Documentação do projeto
└── LICENSE             # Licença do projeto

# Link do site https://d2ztlvqhtiu65m.cloudfront.net

##📖 Guia de Uso
Pré-requisitos
Conta na AWS.
Domínio registrado no Route 53.
Passo a Passo
Criar o bucket S3:
Habilitar para hospedagem estática.
Configurar permissões de leitura pública (ou usar políticas de acesso do CloudFront).
Configurar o CloudFront:
Criar uma distribuição apontando para o bucket S3.
Habilitar HTTPS com um certificado SSL gerado no ACM.
Configurar o Route 53:
Adicionar registros DNS para apontar o domínio para o CloudFront.
Upload dos arquivos:
Fazer upload dos arquivos estáticos para o bucket S3.

###📈 Aprendizados
Configuração de buckets S3 para hospedagem estática.
Gerenciamento de DNS com Route 53.
Uso do CloudFront para distribuição de conteúdo com baixa latência e HTTPS.

#Imagem S3 conexão
c:\Users\Dell\Desktop\24.png

# Imagem Cloudfront conexão
c:\Users\Dell\Desktop\26.png

#Imagem site estático
c:\Users\Dell\Desktop\25.png

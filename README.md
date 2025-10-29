# ☁️ aws-arquitetura-simples

### 🧩 Arquitetura AWS – Exemplo com S3, Lambda e EC2

Este repositório apresenta um **exemplo de arquitetura na AWS**, com diagrama ilustrativo de uma aplicação simples que utiliza serviços como **Amazon S3**, **Lambda**, **CloudFront** e **EC2**.

---

## ⚙️ Componentes da Arquitetura

1. **Usuário (User)**  
   Interage com a aplicação por meio da web.

2. **Amazon CloudFront**  
   Serviço de **CDN (Content Delivery Network)** responsável por entregar o conteúdo de forma rápida e segura ao usuário.

3. **Amazon S3 (Simple Storage Service)**  
   Utilizado para armazenar arquivos e conteúdo estático da aplicação.

4. **AWS Lambda**  
   Responsável por processar eventos e executar código sob demanda, sem necessidade de servidor dedicado.

5. **Amazon EC2 (Elastic Compute Cloud)**  
   Instância que executa aplicações, APIs ou serviços de backend.

---

## 🔄 Fluxo da Arquitetura

1. O usuário acessa a aplicação via navegador.  
2. O conteúdo estático é servido pelo **CloudFront**, que o busca no **S3**.  
3. Solicitações dinâmicas disparam funções **Lambda**.  
4. Quando necessário, a **Lambda** se comunica com uma instância **EC2** para processamentos complexos.  
5. As respostas são entregues novamente via CloudFront ao usuário final.

---

## 🖼️ Diagrama da Arquitetura

![Diagrama da Arquitetura AWS](https://github.com/malumendonca998/aws-arquitetura-simples/blob/main/diagrama-aws.png?raw=true)


---

## 👩‍💻 Autora

**Maria Luiza Mendonça**  
Instrutora de Programação | Estudante de Segurança da Informação  
Apaixonada por tecnologia, automação e cibersegurança 🔐✨

📫 [LinkedIn](https://www.linkedin.com) • [GitHub](https://github.com/malumendonca998)

---

## 🧠 Sobre o Projeto

> Este projeto tem finalidade **educacional**, demonstrando um exemplo simples de arquitetura escalável na **AWS**.  
> Ideal para estudantes e profissionais que desejam entender a integração entre **S3**, **Lambda** e **EC2** em um ambiente real.

---

## 🏗️ Tecnologias Utilizadas

- ☁️ **Amazon Web Services (AWS)**
- 🧠 **AWS Lambda**
- 📦 **Amazon S3**
- 🚀 **Amazon EC2**
- 🌐 **Amazon CloudFront**
- 🧰 **Markdown / GitHub Pages**

---

⭐ Se este repositório te ajudou, deixe uma **estrela** para apoiar o projeto!

# 🚀 Portfólio de Desenvolvimento Full Stack

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)](https://nginx.org/)
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/cloud/)

Bem-vindo ao meu repositório principal! Este é um portfólio abrangente demonstrando minhas habilidades em desenvolvimento full stack, DevOps e cloud computing.

## 🛠️ Stack Tecnológica

### Frontend
- **React.js** - Biblioteca para construção de interfaces de usuário
- **JavaScript/TypeScript** - Linguagens de programação
- **HTML5 & CSS3** - Estrutura e estilização
- **Responsive Design** - Design adaptável para todos os dispositivos

### Backend
- **Node.js** - Runtime JavaScript server-side
- **Express.js** - Framework web minimalista
- **RESTful APIs** - Arquitetura de serviços web
- **Authentication & Authorization** - JWT, OAuth, Session Management

### Banco de Dados
- **MongoDB** - Banco de dados NoSQL orientado a documentos
- **SQLite** - Banco de dados SQL leve e embarcado
- **Database Design** - Modelagem e otimização de dados
- **ODM/ORM** - Mongoose, Sequelize

### DevOps & Infraestrutura
- **Docker** - Containerização e orquestração
- **Nginx** - Servidor web e proxy reverso
- **CI/CD** - Integração e entrega contínua
- **Linux Administration** - Administração de sistemas

### Cloud Computing
- **AWS EC2** - Elastic Compute Cloud
- **Oracle Cloud Infrastructure** - Serviços de nuvem
- **Cloud Deployment** - Deploy e escalabilidade
- **Infrastructure as Code** - Automação de infraestrutura

## 📁 Estrutura do Repositório

```
📦 portfolio-fullstack/
├── 🌐 frontend/
│   ├── react-projects/
│   ├── vanilla-js-apps/
│   └── ui-components/
│
├── ⚙️ backend/
│   ├── nodejs-apis/
│   ├── microservices/
│   └── authentication/
│
├── 🗄️ databases/
│   ├── mongodb-schemas/
│   ├── sqlite-examples/
│   └── data-modeling/
│
├── 🐳 docker/
│   ├── dockerfiles/
│   ├── docker-compose/
│   └── kubernetes/
│
├── 🌊 nginx/
│   ├── configurations/
│   ├── load-balancing/
│   └── ssl-setup/
│
├── ☁️ cloud-deployment/
│   ├── aws-ec2/
│   ├── oracle-cloud/
│   └── terraform/
│
└── 📚 documentation/
    ├── setup-guides/
    ├── best-practices/
    └── troubleshooting/
```

## 🚀 Projetos Destacados

### 1. E-commerce Full Stack
**Tecnologias:** React, Node.js, MongoDB, Docker, AWS EC2
- Sistema completo de e-commerce com painel administrativo
- Integração com gateways de pagamento
- Deploy automatizado com Docker

### 2. Sistema de Gerenciamento de Tarefas
**Tecnologias:** React, Express.js, SQLite, Nginx
- Interface responsiva e intuitiva
- API RESTful robusta
- Autenticação JWT

### 3. Microserviços Containerizados
**Tecnologias:** Node.js, Docker, MongoDB, Oracle Cloud
- Arquitetura de microserviços
- Orquestração com Docker Compose
- Deploy em Oracle Cloud Infrastructure

## 🔧 Como Executar os Projetos

### Pré-requisitos
```bash
# Node.js (versão 16+)
node --version

# Docker
docker --version

# Docker Compose
docker-compose --version
```

### Instalação Rápida
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/portfolio-fullstack.git
cd portfolio-fullstack

# Instale as dependências
npm install

# Execute com Docker
docker-compose up -d

# Ou execute localmente
npm run dev
```

## 🌐 Configuração de Deploy

### AWS EC2
```bash
# Configuração do servidor
sudo apt update && sudo apt upgrade -y
sudo apt install nginx docker.io docker-compose -y

# Clone e execute
git clone https://github.com/seu-usuario/portfolio-fullstack.git
cd portfolio-fullstack
docker-compose -f docker-compose.prod.yml up -d
```

### Oracle Cloud
```bash
# Configuração da instância
sudo yum update -y
sudo yum install -y docker nginx

# Configure o firewall
sudo firewall-cmd --permanent --add-port=80/tcp
sudo firewall-cmd --permanent --add-port=443/tcp
sudo firewall-cmd --reload
```

## 📊 Monitoramento e Logs

### Nginx Logs
```bash
# Logs de acesso
tail -f /var/log/nginx/access.log

# Logs de erro
tail -f /var/log/nginx/error.log
```

### Docker Logs
```bash
# Logs do container
docker logs -f container_name

# Logs de todos os serviços
docker-compose logs -f
```

## 🔒 Segurança

### Práticas Implementadas
- ✅ Autenticação JWT
- ✅ Validação de entrada
- ✅ Rate limiting
- ✅ HTTPS/SSL
- ✅ CORS configurado
- ✅ Sanitização de dados
- ✅ Backup automatizado

### Configuração SSL
```nginx
server {
    listen 443 ssl;
    ssl_certificate /path/to/certificate.pem;
    ssl_certificate_key /path/to/private.key;
    ssl_protocols TLSv1.2 TLSv1.3;
}
```

## 📈 Performance

### Otimizações
- **Frontend:** Code splitting, lazy loading, PWA
- **Backend:** Caching, connection pooling, clustering
- **Database:** Indexação, query optimization
- **Nginx:** Gzip, caching, load balancing

### Métricas
- Tempo de carregamento < 2s
- Disponibilidade > 99.9%
- Tempo de resposta API < 200ms

## 🤝 Contribuição

Contribuições são bem-vindas! Por favor, siga estas diretrizes:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📚 Recursos e Aprendizado

### Documentações Úteis
- [Node.js Documentation](https://nodejs.org/docs/)
- [React Documentation](https://reactjs.org/docs/)
- [Docker Documentation](https://docs.docker.com/)
- [Nginx Documentation](https://nginx.org/en/docs/)
- [AWS EC2 Documentation](https://docs.aws.amazon.com/ec2/)
- [Oracle Cloud Documentation](https://docs.oracle.com/cloud/)

### Cursos e Certificações
- AWS Certified Solutions Architect
- Docker Certified Associate
- Oracle Cloud Infrastructure Certified

## 📞 Contato

- **LinkedIn:** [Seu LinkedIn](https://linkedin.com/in/seu-perfil)
- **Email:** seu.email@exemplo.com
- **Portfolio:** [seu-portfolio.com](https://seu-portfolio.com)
- **GitHub:** [@seu-usuario](https://github.com/seu-usuario)


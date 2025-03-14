## ☕ CoffeeOnrain  - A Rede Social para Quem Ama Conversar e Café
***

O **CoffeeNet** é uma **rede social** criada para conectar pessoas por meio de discussões envolventes, tópicos em alta e interações reais—assim como uma boa conversa acompanhada de café. Esse projeto foi desenvolvido com foco em **desempenho, escalabilidade** e **experiência do usuário**, utilizando as melhores ferramentas e práticas do ecossistema **Django**. Abaixo são as tecnologias que são utilizados nesse projeto.

### 🔧 Tecnologias e Frameworks

- **Django**:  
    Framework principal para o desenvolvimento do backend. Ele oferece uma estrutura robusta e segura para a criação de aplicações web escaláveis e de alta performance, com suporte completo para gerenciamento de banco de dados, autenticação e admin.
    
- **Django AllAuth**:  
    Utilizado para **autenticação de usuários**, incluindo login, registro, recuperação de senha e perfis personalizados. Ele facilita a integração com plataformas externas (como login social via Google ou Facebook), garantindo uma experiência de autenticação fluida.
    
- **PostgreSQL**:  
    Banco de dados relacional robusto para armazenamento das informações de usuários, postagens, comentários e interações. O PostgreSQL foi escolhido por sua estabilidade e desempenho em sistemas de alta demanda.

### 🐳 Docker

- **Docker**: A aplicação está containerizada utilizando Docker, permitindo uma experiência de desenvolvimento mais fluida e ambientes de execução padronizados. Com Docker, o **CoffeeNet** pode ser executado de forma isolada e consistente em qualquer sistema operacional sem a necessidade de configurar manualmente o ambiente.
    
- **Docker Compose**: O projeto também utiliza **Docker Compose** para orquestrar múltiplos containers, como o container do backend (Django), banco de dados (PostgreSQL), e o cache (Redis). Isso facilita a configuração e execução do ambiente de desenvolvimento e produção.


### 🔒 Segurança

- **Autenticação baseada em tokens**: A aplicação utiliza tokens JWT (JSON Web Tokens) para garantir a segurança nas requisições da API.
- **Proteção contra CSRF e XSS**: Asseguramos que a aplicação esteja protegida contra ataques comuns, como Cross-Site Request Forgery (CSRF) e Cross-Site Scripting (XSS), utilizando as funcionalidades nativas do Django.

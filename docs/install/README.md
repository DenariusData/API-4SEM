# 📖 Manual de Instalação - Denarius Data

Bem-vindo ao guia de instalação do **Denarius Data**! Este documento vai te orientar passo a passo para configurar e executar a aplicação completa do projeto.

## 🎯 O que você vai instalar?

Este projeto é composto por:
- **Frontend**: Interface web desenvolvida em Vue.js 3
- **Backend**: API RESTful desenvolvida em Spring Boot (Java 21)
- **Banco de Dados**: Oracle Database (via Oracle Cloud)
- **Docker**: Para orquestrar e executar todos os serviços

## 📋 Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:

### Obrigatório:
- **[Git](https://git-scm.com/downloads)** - Para clonar o repositório
- **[Docker Desktop](https://www.docker.com/products/docker-desktop/)** - Para Windows, Linux ou Mac
  - ⚠️ Certifique-se de que o Docker Desktop está em execução antes de prosseguir

### Opcional (apenas se NÃO usar Docker):
- **[Node.js 20+](https://nodejs.org/)** e npm - Para executar o frontend manualmente
- **[Java 21](https://www.azul.com/downloads/?version=java-21-lts&package=jdk#zulu)** - Para executar o backend manualmente

## 🚀 Instalação Rápida (Recomendado)

### Passo 1: Clone o repositório

Abra um terminal e execute:

```bash
git clone https://github.com/DenariusData/API-4SEM.git
cd API-4SEM
```

### Passo 2: Baixe os submódulos

O projeto utiliza submódulos Git para o frontend e backend:

```bash
git submodule update --init --recursive
```

### Passo 3: Configure o Oracle Wallet

O projeto utiliza Oracle Database com autenticação via Wallet. Certifique-se de que a pasta `Wallet_radarius` está presente em:

```
API-4SEM-BACKEND/Wallet_radarius/
```

> 💡 **Nota**: Os arquivos do Wallet são necessários para conectar ao banco de dados Oracle. Entre em contato com a equipe se você não tiver acesso a esses arquivos.

### Passo 4: Inicie a aplicação com Docker

No diretório raiz do projeto (`API-4SEM`), execute:

```bash
docker-compose up --build
```

Este comando irá:
- ✅ Construir as imagens Docker do frontend e backend
- ✅ Iniciar os containers
- ✅ Configurar a rede entre os serviços
- ✅ Disponibilizar a aplicação

**Aguarde alguns minutos** enquanto o Docker faz o download das dependências e constrói os containers. Você verá logs no terminal indicando o progresso.

### Passo 5: Acesse a aplicação

Após a inicialização completa, acesse:

- **🌐 Frontend**: http://localhost
- **🔧 API Backend**: http://localhost:8080
- **💚 Health Check**: http://localhost:8080/actuator/health

## 🎨 Modo de Desenvolvimento

Se você preferir executar a aplicação em modo de desenvolvimento (sem Docker):

### Frontend
```bash
cd API-4SEM-FRONTEND
npm install
npm run dev
```
Acesse em: http://localhost:5173

### Backend
```bash
cd API-4SEM-BACKEND
./gradlew bootRun
```
ou
```bash
java -jar build/libs/radarius-backend.jar
```

## 🛠️ Comandos Úteis do Docker

### Ver logs da aplicação
```bash
# Ver todos os logs
docker-compose logs -f

# Ver logs apenas do backend
docker-compose logs -f backend

# Ver logs apenas do frontend
docker-compose logs -f frontend
```

### Parar a aplicação
```bash
docker-compose down
```

### Parar e remover volumes
```bash
docker-compose down -v
```

### Reconstruir após alterações
```bash
docker-compose up --build
```

### Executar em segundo plano (detached mode)
```bash
docker-compose up -d
```

## 🔧 Resolução de Problemas

### ❌ Porta 80 ou 8080 já está em uso

**Problema**: Outro serviço está usando as portas necessárias.

**Solução**: Edite o arquivo `docker-compose.yml` e altere as portas:

```yaml
services:
  backend:
    ports:
      - "8081:8080"  # Mude 8080 para 8081
  frontend:
    ports:
      - "3000:80"    # Mude 80 para 3000
```

### ❌ Docker não está em execução

**Problema**: O Docker Desktop não foi iniciado.

**Solução**: 
- No Windows: Abra o Docker Desktop pelo menu Iniciar
- No Linux: Execute `sudo systemctl start docker`
- No Mac: Abra o Docker Desktop pela barra de aplicativos

### ❌ Erro de conexão com o banco de dados

**Problema**: Arquivos do Wallet estão ausentes ou inválidos.

**Solução**:
1. Verifique se a pasta `API-4SEM-BACKEND/Wallet_radarius` existe
2. Verifique se os arquivos do Wallet estão presentes
3. Entre em contato com a equipe para obter os arquivos corretos

### ❌ Submódulos vazios

**Problema**: As pastas `API-4SEM-BACKEND` e `API-4SEM-FRONTEND` estão vazias.

**Solução**:
```bash
git submodule update --init --recursive
```

### ❌ Build falhou

**Problema**: Erro durante a construção das imagens Docker.

**Solução**:
1. Limpe as imagens antigas:
   ```bash
   docker-compose down --rmi all
   docker system prune -a
   ```
2. Reconstrua:
   ```bash
   docker-compose up --build
   ```

## 📊 Verificando se está tudo funcionando

Execute estas verificações para garantir que tudo está OK:

1. ✅ **Docker**: `docker ps` deve mostrar 2 containers rodando
2. ✅ **Backend**: Acesse http://localhost:8080/actuator/health - deve retornar `{"status":"UP"}`
3. ✅ **Frontend**: Acesse http://localhost - deve carregar a página inicial
4. ✅ **Logs**: `docker-compose logs` não deve mostrar erros críticos

## 📚 Próximos Passos

Agora que a aplicação está instalada e rodando:

1. 📖 Consulte o [Manual do Usuário](../user/README.md) para aprender a usar o sistema
2. 🔍 Veja a [Documentação da API](../../README.md#documentacao-api) para entender os endpoints
3. 🗄️ Confira a [Modelagem do Banco de Dados](../../README.md#modelagem-de-banco-de-dados)

## 💬 Precisa de Ajuda?

Entre em contato com a equipe Denarius Data:

- 📧 **Email de Suporte**: davisfs2110@gmail.com

---

<p align="center">
  Feito com ❤️ e 🤖 pela equipe <strong>Denarius Data</strong>
</p>

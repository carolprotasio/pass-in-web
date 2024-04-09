# Pass.in - Gestão de Participantes em Eventos Presenciais
A plataforma Pass.in é uma ferramenta de gerenciamento de participantes de eventos, equipada com um painel de controle para os organizadores e participantes.

Um dos aspectos mais destacados deste projeto é a utilização de persistência de estados de URL, garantindo a continuidade das interações dos usuários mesmo após a atualização da página. Além disso, destaca-se a implementação de uma interface completamente padronizada, seguindo os princípios de design com o auxílio do Tailwind CSS.

# 🚀 Características

- Integração com API em Node.js
- Pesquisa por participante
- Paginação
- Definir instruções de URL com parâmetros de consulta
- [Swagger](https://nlw-unite-nodejs.onrender.com/docs/static/index.html)
- Diagrama ERD
<img src="https://efficient-sloth-d85.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F08f749ff-d06d-49a8-a488-9846e081b224%2F8f354dec-0218-43af-a16c-16a86f2d82b0%2Ferd.svg?table=block&id=1d4a760d-238b-477a-ac6d-c03e0bd682af&spaceId=08f749ff-d06d-49a8-a488-9846e081b224&userId=&cache=v2" alt="Diagrama ERD" style="width:800px;height:800px;">

# Preview

![Vídeo-Pass-in-web](src/assets/pass-in.gif)
![Pass-in-web-pictute](https://github.com/carolprotasio/pass-in-web/blob/master/src/assets/pass-in-web-pic.png)

# 🛠️ Tecnologias utilizada

- React
- Vite
- TypeScript
- Tailwind
- Lucide icons
- Backend com Node.js e Prisma

# 📚 Blibiotecas

- Tailwind-merge
- FakerJS
- DayJS

# 👷 Para executar o projeto:
## Inicie o front-end

Clonar repositório

```
https://github.com/carolprotasio/pass-in-web.git
```
Instalar dependências

```
npm i
```
Iniciar aplicação

```
npm run dev
```
## Configure o back-end

Backend utilizado disponível em [RocketNodeJs](https://github.com/rocketseat-education/nlw-unite-nodejs)


**Você precisa instalar o [Node.js](https://nodejs.org/en/download/) e depois, clonar o projeto via HTTPS, usando o comando abaixo:**

```
git clone https://github.com/rocketseat-education/nlw-unite-nodejs.git
```

**Instalar dependências**

```
npm i
```

**Criar o arquivo .env e colar o seguinte código**
```env
DATABASE_URL="file:./dev.db"
```

**Preencha o banco de dados com o comando**
```bash
npx prisma db seed
```

**Iniciar o servidor**
```bash
npm run dev
```

# Créditos
Este projeto foi desenvolvido com base no tutorial oferecido pela Rocketseat durante o evento NJW Unite. Agradeço à equipe da Rocketseat por fornecer recursos valiosos e conhecimento técnico.

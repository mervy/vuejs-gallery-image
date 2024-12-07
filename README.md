# vuejs-gallery-image

Criar uma galeria de imagens com Vue.js no frontend, Node.js no backend, MongoDB como banco de dados e usando ES6

A estrutura do projeto pode ser algo como:

```bash
project/
├── backend/
│   ├── .env
│   ├── server.js
│   ├── routes/
│   │   └── images.js
│   ├── models/
│   │   └── Image.js
│   └── uploads/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── ImageGallery.vue
│   │   │   ├── UploadImage.vue
│   │   └── App.vue
│   ├── .env
│   └── package.json
└── package.json
```

2. Configurando o Backend

Instale Dependências:

```bash
mkdir backend && cd backend
npm init -y
npm install express mongoose dotenv multer cors
npm install nodemon --save-dev
```

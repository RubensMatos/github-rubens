# Quickstart (Hub)

## 1) Rodar o site de portfólio deste repositório

```bash
cd portfolio
python3 -m http.server 8080
```

Acesse: `http://127.0.0.1:8080`

## 2) Clonar e rodar projetos dedicados

### Python Public API

```bash
git clone https://github.com/RubensMatos/python-public-api.git
cd python-public-api
python3 -m app.server --host 127.0.0.1 --port 8000
```

### PHP CRUD API

```bash
git clone https://github.com/RubensMatos/php-crud-api.git
cd php-crud-api
php -S 127.0.0.1:8081 -t public public/index.php
```

### React LeadOps Dashboard

```bash
git clone https://github.com/RubensMatos/react-leadops-dashboard.git
cd react-leadops-dashboard
npm install
npm run dev -- --host 127.0.0.1 --port 5174
```

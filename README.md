# comando github

## 🚀 1.0 Iniciar um repositório
git init

## 1.2 Cria sua branch de desenvolvimento
git checkout -b dev

## 2. Trabalha normalmente
- git add .
- git commit -m "feature nova"
- git push origin dev

### 🚫 Nenhum deploy é feito!

# 3. Faz merge para main quando quiser deploy
- git checkout main
- git merge dev
- git push origin main

# ✅ Agora o GitHub Actions roda o deploy!

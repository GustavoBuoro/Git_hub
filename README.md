# 📌 Guia Rápido Git e GitHub

## 🚀 Como subir um projeto no GitHub (primeiro push)

| Etapa | Comando |
|-------|----------|
| 1️⃣ Iniciar repositório | `git init` |
| 2️⃣ Adicionar arquivos | `git add .` |
| 3️⃣ Primeiro commit | `git commit -m "Primeiro commit"` |
| 4️⃣ Conectar ao repositório remoto | `git remote add origin URL_DO_REPOSITORIO` |
| 5️⃣ Ajustar branch principal | `git branch -M main` |
| 6️⃣ Enviar para o GitHub | `git push -u origin main` |

---

## 💾 Fazer novos commits

```bash
git add .
git commit -m "Mensagem do commit"
git push origin main

git clone URL_DO_REPOSITORIO
cd NOME_DIRETORIO
git checkout -b nome-da-branch   # cria nova branch
git add .
git commit -m "Alterações"
git push -u origin nome-da-branch

git pull origin main

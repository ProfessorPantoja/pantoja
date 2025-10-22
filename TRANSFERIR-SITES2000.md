# 🚀 Script para Transferir Sites2000

## 📝 COPIE E COLE NO SEU TERMINAL WINDOWS:

### **1. Abra o PowerShell ou CMD**

### **2. Cole estes comandos (um de cada vez):**

```bash
# Vai para sua pasta de usuário
cd C:\Users\%USERNAME%

# Clona a branch de transferência (tem todos os arquivos)
git clone -b claude/transfer-sites2000-011CUM9DgpwKgnDhNXeRJmCF https://github.com/ProfessorPantoja/pantoja.git temp-sites2000

# Clona o repo sites2000 vazio
git clone https://github.com/ProfessorPantoja/sites2000.git

# Copia os arquivos importantes
xcopy temp-sites2000\templates sites2000\templates /E /I
xcopy temp-sites2000\docs sites2000\docs /E /I
copy temp-sites2000\README.md sites2000\
copy temp-sites2000\COMO-CRIAR-REPO-GITHUB.md sites2000\

# Entra na pasta sites2000
cd sites2000

# Commita tudo
git add .
git commit -m "Commit inicial: Negócio de templates de sites"
git push origin main

# Limpa a pasta temporária
cd ..
rmdir /S /Q temp-sites2000
```

---

## ✅ PRONTO!

Depois disso, acesse:
https://github.com/ProfessorPantoja/sites2000

E verá todos os arquivos lá! 🎉

---

**Tempo total:** 2-3 minutos

*21/10/2025 - 23:50*

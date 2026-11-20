# Marcio Cezar Silva Caldeira

Comecei em suporte técnico e acabei escrevendo as ferramentas que a equipe usava.
Hoje trabalho com **C# / .NET**, automação de processos e sistemas internos.

---

### O que eu construí

**🎨 [Render BIM](https://github.com/Marcio282003/portfolio/blob/main/CASO-01-Render-BIM.md)** — plugin de renderização em tempo real para Autodesk Revit
Visualizador 3D próprio em Direct3D 11, rodando **em processo separado** do Revit — um crash de GPU não derruba o trabalho do arquiteto. 21 versões entregues, 147 testes automatizados, exportador glTF escrito do zero quando a ponte oficial da Epic falhou.
`C#` `.NET 8` `Direct3D 11` `Revit API`

**📊 [Registro de Horas](https://github.com/Marcio282003/portfolio/blob/main/CASO-02-Registro-de-Horas.md)** — diagnóstico e correção de um sistema em produção
Os totais de horas mudavam sozinhos entre dois carregamentos da página. A causa era paginação ordenada por uma coluna não única: ~70 registros duplicavam e ~70 sumiam a cada leitura. Conferido contra o banco, obra por obra — **11 de 11 corretas contra 4 de 11**. A correção eram 3 linhas.
`JavaScript` `PostgreSQL` `Supabase` `SQL`

**📦 [MC-Blocks](https://github.com/Marcio282003/portfolio/blob/main/CASO-03-MC-Blocks.md)** — biblioteca de famílias para Revit, substituindo ferramenta comercial
**32 mil famílias, 13 GB**, lidas direto do servidor da empresa. Compila para três versões do Revit a partir do mesmo código-fonte (.NET 8 e .NET Framework 4.8). Auditando o próprio código, encontrei o modo de falha que provavelmente derrubava a ferramenta anterior: exceção na inicialização faz o add-in sumir da faixa de opções sem aviso.
`C#` `WPF` `Revit API` `PowerShell`

---

### Outros repositórios

- **[mf-dev-backend-2026](https://github.com/Marcio282003/mf-dev-backend-2026)** — aplicação ASP.NET Core com CRUD, relatórios, autenticação com senha criptografada e autorização por perfil
- **[viavoz-responsive](https://github.com/Marcio282003/viavoz-responsive)** — sistema web de tarefas com dois perfis de acesso, em PHP

---

### Stack

**Mais forte:** C# · .NET 8 · SQL
**Uso com frequência:** JavaScript · PostgreSQL / Supabase · PHP · WPF
**Domínio específico:** Autodesk Revit API · automação com PowerShell

---

### Contexto

Técnico de suporte por 1 ano e 7 meses na **VIAVOZ LTDA**, empresa de engenharia e arquitetura. Comecei atendendo chamados e terminei automatizando o trabalho das equipes de projeto — foi daí que saíram os três casos acima.

Cursando **Análise e Desenvolvimento de Sistemas** na PUC Minas.

---

📫 **marciogamercaldeira@gmail.com**

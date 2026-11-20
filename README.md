# Marcio Cezar Silva Caldeira

Comecei em suporte técnico e acabei entregando as ferramentas que a equipe usava.
Automatizo processos de engenharia: plugins para Revit, sistemas internos e correção de dados.

Cursando **Análise e Desenvolvimento de Sistemas** na PUC Minas.

### → **[marcio282003.github.io/portfolio](https://marcio282003.github.io/portfolio/)**

---

### O que eu entreguei

**🎨 [Render BIM](https://github.com/Marcio282003/portfolio/blob/main/CASO-01-Render-BIM.md)** — plugin de renderização em tempo real para Autodesk Revit
Alternativa interna ao Enscape, com visualizador 3D rodando **em processo separado** do Revit — um crash de GPU não derruba o trabalho do arquiteto. 21 versões entregues, 147 testes automatizados, testado e validado dentro do Revit a cada ciclo.
`C#` `.NET 8` `Direct3D 11` `Revit API`

**📊 [Registro de Horas](https://github.com/Marcio282003/portfolio/blob/main/CASO-02-Registro-de-Horas.md)** — diagnóstico e correção de um sistema em produção
Os totais de horas mudavam sozinhos entre dois carregamentos da página. A causa era paginação ordenada por uma coluna não única: ~70 registros duplicavam e ~70 sumiam a cada leitura. Conferido contra o banco, obra por obra — **11 de 11 corretas contra 4 de 11**. A correção eram 3 linhas, que decidi **não** aplicar: o sistema era de outra pessoa e estava em produção.
`JavaScript` `PostgreSQL` `Supabase` `SQL`

**📦 [MC-Blocks](https://github.com/Marcio282003/portfolio/blob/main/CASO-03-MC-Blocks.md)** — biblioteca de famílias para Revit, substituindo ferramenta comercial
**32 mil famílias, 13 GB**, lidas direto do servidor da empresa. Compila para três versões do Revit a partir do mesmo código-fonte. Implantado na equipe de arquitetura e, depois, numa empresa parceira.
`C#` `WPF` `Revit API` `PowerShell`

> Os três foram construídos **com apoio intensivo de IA**. Meu papel foi especificar, testar,
> decidir escopo e risco, e conduzir a implantação. Cada estudo de caso detalha essa divisão.

---

### Outros repositórios

- **[mf-dev-backend-2026](https://github.com/Marcio282003/mf-dev-backend-2026)** — aplicação ASP.NET Core com CRUD, relatórios, autenticação com senha criptografada e autorização por perfil
- **[viavoz-responsive](https://github.com/Marcio282003/viavoz-responsive)** — sistema web de tarefas com dois perfis de acesso, em PHP

---

### Tecnologias com que trabalho

`C#` · `.NET 8` · `SQL` · `PostgreSQL / Supabase` · `JavaScript` · `PHP` · `WPF`
`Autodesk Revit API` · `PowerShell`

Estou aprendendo os fundamentos de programação na faculdade agora. O que entreguei até aqui
veio de entender bem o problema, testar com rigor e levar o projeto até o fim.

---

### Contexto

Técnico de suporte por 1 ano e 7 meses na **VIAVOZ LTDA**, empresa de engenharia e arquitetura.
Comecei atendendo chamados e terminei automatizando o trabalho das equipes de projeto — foi daí
que saíram os três casos acima.

---

📫 **marciogamercaldeira@gmail.com**

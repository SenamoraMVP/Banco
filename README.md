# Banco
Banco de Dados Relacional do senamora. Contendo 7 tabelas, nosso mvp poderá sobrer alterações
# Projeto Senamora - Estrutura de Arquivos

Este repositório contém os scripts de banco de dados e o modelo relacional referentes ao sistema **Senamora**.

---

## 📁 Estrutura de Conteúdo

O arquivo compactado `Senamora ` é composto pela pasta raiz `Senamora`, a qual armazena os seguintes componentes:

```text
Senamora 
├── senamora_curtidas.sql
├── senamora_diagrama.mwb
├── senamora_fotos.sql
├── senamora_interesses.sql
├── senamora_matches.sql
├── senamora_preferencias.sql
├── senamora_usuarios.sql
└── senamora_usuario_interesses.sql
```

---

## 📄 Detalhamento dos Componentes

### 1. Modelo de Banco de Dados (Diagrama EER)
* **`senamora_diagrama.mwb`**  
  Arquivo de modelo relacional nativo do **MySQL Workbench** (`.mwb`), contendo a representação visual, diagramação de tabelas, atributos e relacionamentos da base de dados do sistema.

### 2. Scripts SQL de Banco de Dados (`.sql`)
A estrutura de dados é composta por 7 arquivos de script SQL:

* **`senamora_usuarios.sql`**  
  Script SQL contendo a estrutura/dados relacionados ao cadastro principal de usuários do sistema.

* **`senamora_curtidas.sql`**  
  Script SQL contendo os registros ou estrutura referentes às curtidas realizadas entre usuários.

* **`senamora_matches.sql`**  
  Script SQL responsável pela armazenagem e gerenciamento das combinações (*matches*) efetuadas.

* **`senamora_fotos.sql`**  
  Script SQL contendo os dados e referências das fotografias associadas aos perfis de usuários.

* **`senamora_interesses.sql`**  
  Script SQL responsável pelo catálogo de interesses disponíveis na aplicação.

* **`senamora_usuario_interesses.sql`**  
  Script SQL que realiza o vinculo N:M (muitos para muitos) entre os usuários e seus respectivos interesses selecionados.

* **`senamora_preferencias.sql`**  
  Script SQL para armazenamento das configurações e preferências de perfil/busca dos usuários.

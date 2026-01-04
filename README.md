# SaaSERp

Projeto PHP do painel SaaSERp.

## Requisitos
- PHP
- MySQL / MariaDB
- Git
- Git LFS (para arquivos grandes como .zip)

## Clonar (read-only público)
```bash
git clone https://github.com/HugoGandyEC/SaaSERp.git
cd SaaSERp
```

## Git LFS
Este repositório usa Git LFS para arquivos binários (ex.: `.zip`). Antes de clonar/atualizar no seu ambiente, instale e inicialize o Git LFS:

```powershell
# Windows (winget)
winget install --id Git.GitLFS -e --source winget
git lfs install
# depois de clonar
git lfs pull
```

## Configurar localmente
- copie um arquivo de ambiente (se existir) `cp .env.example .env` e ajuste as credenciais
- importe o banco de dados se necessário: `mysql -u usuario -p nome_db < erp.sql`
- instale dependências (se usar Composer): `composer install`

## Observações
- Evite commitar arquivos grandes sem usar Git LFS; arquivos maiores que 100MB serão rejeitados pelo GitHub.
- O arquivo `erp.sql` contém o esquema/banco do projeto.

## Contato
Para dúvidas: abra uma issue no repositório.
Sistema Base para Criar outros Projetos

# Política de backups

## Backup de la base de datos

Se realizará una copia diaria con:

```bash
mysqldump -u root -p empresa > backup.sql
```

## Backup de archivos web

Se realizará copia del contenido web con:

```bash
rsync -av /var/www/html /backup/
```

## Frecuencia

- Diario
- Retención de 7 días

## Objetivo

Garantizar recuperación rápida ante fallo del sistema.
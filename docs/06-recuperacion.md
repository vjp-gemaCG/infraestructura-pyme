# Recuperación ante desastres

## Procedimiento

1. Restaurar servidor Ubuntu
2. Instalar Apache
3. Restaurar archivos web
4. Restaurar base de datos
5. Verificar funcionamiento

## Restauración de base de datos

```bash
mysql -u root -p empresa < backup.sql
```

## Restauración web

```bash
rsync -av /backup/html /var/www/html
```
# Operación diaria

## Revisiones diarias

- Comprobar que Apache está activo
- Revisar uso de CPU y memoria
- Verificar espacio en disco
- Confirmar que MySQL responde

## Logs

Revisar:

```bash
/var/log/apache2/access.log
/var/log/apache2/error.log
```

## Servicios

Reiniciar si es necesario:

```bash
sudo systemctl restart apache2
sudo systemctl restart mysql
```
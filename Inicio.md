# 🏠 Inicio

## 📌 Proyectos activos
```dataview
TABLE estado, fecha_fin AS "Entrega"
FROM "10-Proyectos"
WHERE estado = "activo"
SORT fecha_fin ASC
```

## 📥 Pendiente por organizar
```dataview
LIST FROM "00-Inbox"
```

## 📝 Últimas notas
```dataview
TABLE file.mtime AS "Modificada"
FROM "" WHERE file.name != "Inicio"
SORT file.mtime DESC LIMIT 10
```

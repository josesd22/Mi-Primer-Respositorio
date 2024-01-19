---
sidebar_position: 1
---
# Class BaseAuditableEntity

Clase base abstracta para entidades auditables.
```cs
public abstract class BaseAuditableEntity : BaseEntity
```
1. **Created** Obtiene o establece la fecha y hora de creación de la entidad
    ```cs
    public DateTimeOffset Created { get; set; }
    ```

2. **CreatedBy** Obtiene o establece el identificador del creador de la entidad.
     ```cs
      public string? CreatedBy { get; set; }
    ```
3. **LasModifield** Obtiene o establece la fecha y hora de la última modificación de la entidad.

    ```cs
       public DateTimeOffset LastModified { get; set; }
    ```
4. **LasModifiedBy** Obtiene o establece el identificador del último modificador de la entidad
     ```cs
       public string? LastModifiedBy { get; set; }
    ```
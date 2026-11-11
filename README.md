
```mermaid
erDiagram
    REVISION {        
       int id PK        
       string descripcion
       int horas       
    }
    PINTURA {        
       int id PK        
       string descripcion
       int horas
       int material      
    }
    MECANICA {        
       int id PK        
       string descripcion
       int horas
       int material
    } 
```

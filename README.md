# PatronMvcMonolito


               
 El proyecto "BibliotecaMonolito" tiene las referencias de paquete siguientes
   [net11.0]: 
   Paquete de nivel superior                   Solicitado                   Resuelto  

   # dotnet list package           
   > Microsoft.AspNetCore.OpenApi              11.0.0-preview.6.26359.118   11.0.0-preview.6.26359.118
   > Microsoft.EntityFrameworkCore             11.0.0-preview.6.26359.118   11.0.0-preview.6.26359.118
   > Microsoft.EntityFrameworkCore.Design      11.0.0-preview.6.26359.118   11.0.0-preview.6.26359.118
   > Microsoft.EntityFrameworkCore.Sqlite      11.0.0-preview.6.26359.118   11.0.0-preview.6.26359.118
   > Swashbuckle.AspNetCore                    10.2.3    
# comando para ejecutar paquetes  
dotnet add package Microsoft.EntityFrameworkCore.Desing --version 11.0.0


# Comando para Migraciones
 dotnet ef migrations add Init    

Comando para Actualizar modelos 

dotnet ef database update    
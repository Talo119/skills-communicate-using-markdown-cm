# Markdown Example


>*Este es un ejercicio para aprender markdown.*

1. Primero creé el PR.
2. Luego abri el index.md
3. Y por último edité el archivo.

``` C#
Notas nota_item = new Notas()
        {
            Id = 0,
            CantidadSacos = 100,
            PesoBruto = 100,
            Tara = 1,
            Humedad = 10,
            GM = 0,
            Otros = 0,
            Descuento = 9.9M,
            Onzas = 0,
            PesoNeto = 89.1M
        };
        var result = await localRepo.SaveItemAsync(nota_item);
        
        var notas = await localRepo.GetItemsAsync();
        
        notas_peso = notas;
```

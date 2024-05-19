# Antes de empezar
- Bindeo = Asignar una tecla a una acción
- Algunos de estos bindeos se pueden hacer desde la consola del juego, otros solo funcionan si se ejecutan desde un autoexec
- **LEER ATENTAMENTE PORQUE PUEDE REEMPLAZAR BINDEOS DE TECLAS YA EXISTENTES**
- 
## Instalación de los cfg

1. [Descargar los archivos](https://github.com/Santiagofamo18/CS2-Configs/archive/refs/heads/main.zip)
2. Ir al directorio de `cfg`

**Windows** 

`C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`

> [!Tip] 
> Puedes pulsar el atajo de teclado `Win + R` y pegar la ruta de arriba

**Linux**

`~/.steam/steam/steamapps/common/Counter-Strike Global Offensive/csgo/cfg/`

3. Pegar los archivos .cfg

## Autoexec
Antes de nada, para habilitar el Autoexec, hacer click derecho al juego en la biblioteca > Propiedades y en _Parámetros de lanzamiento_ escribir:
```
+exec autoexec.cfg
```
![imagen](https://github.com/Santiagofamo18/CS2-Configs/assets/94525179/8f57d649-9867-49d9-8646-cfa5f2f0e870)

### Binds por separado 
Para añadir a un .cfg existente. 

Para cambiar la tecla reemplaza el valor de la tecla por defecto, por ejemplo

![imagen](https://github.com/Santiagofamo18/CS2-Configs/assets/94525179/11f7a789-ca2f-4e11-8b1d-bbab7f4baf64)

Si la tecla por defecto es `t` y lo queremos cambiar por una `q`, lo reemplazamos

![imagen](https://github.com/Santiagofamo18/CS2-Configs/assets/94525179/8c41f2e2-b6d3-40f3-a595-3484c7af8842)

#### Crouch Jump
Salta y se agacha en el aire, para boosts
**Tecla por defecto:** `space`

```
//CROUCH JUMP
alias "+hjump" "+jump; +duck"; alias "-hjump" "-jump; -duck"; bind space "+hjump"
```

#### Drop Bomb
Suelta la bomba y te equipa automaticamente el arma principal, en su defecto te equipa el arma secundaria.
**Tecla por defecto:** `t`
```
//DROP BOMB
alias "+bomb" "slot3; slot5; drop"; alias "-bomb" "slot2; slot1"; bind "t" +bomb
```

#### QuickSwitch 
Cambia al cuchillo cuando se pulsa y vuelve al arma anterior cuando se suelta la tecla.
Útil para dejar de apuntar con el AWP si tienes el auto-scope activado. Tambien queda como muy pro

Tecla por defecto `q`
```
alias "+qsw" "slot3"; alias -qsw "lastinv";bind "q" +qsw
``` 

#### Salto con rueda del ratón (Bunny Hop)

##### Salto con rueda arriba
```
// Scroll Up to Jump
bind "mwheelup" +jump
```

##### Salto con rueda abajo
```
// Scroll Down to Jump
bind "mwheeldown" +jump
```






# Mudando a cor de um marcador
1. Para marcarmos um text usamos:
   ```
   <mark>Textp marcado</mark>
   ```
2. Usamos o background-color:cor; para mudar a cor da marcação
```
<mark style="background-color:blue;">um texto marcado</mark>

```
# Mudando a cor de todos os marcadores
* Para mudar a cor de todos os markadores que usarmos naquela pagina html usamos a tag style:
```
    <style>
        mark{
            background-color:cor;
        }
    </style>
```
# Texto grande e pequeno
* Para fazer um texto grande usamos a tag "big" , mas não utilzar mais , é semanticamente errado.
```
<big> Texto grande </big>
```
* Para fazer um texto pequeno ainda usamos a tag "small" 
  ```
  <small>Texto pequeno</small>
  ```

# Por que o big se tornou obsoleto?
* porque ele não passa nenhum valor semântico, hoje usamos o font-size no css para aumentar um texto

# Textos deletado (del) e inserido (ins)
* Assim são <del>textos Deletados</del> 
```
<del> Texto Deletado</del>

```
* Assim são os <ins>Textos inseridos</ins> ou sublinhados.
  ```
  <ins>Texto inserido</ins>
  ```
# Diferença entre as tags ins e u
* INS é semântico.
  
# Sobrescrito (sup) e subscrito (sub)
* Define um texto sobrescrito **X<sup>2</sup>** Igual o símbolo de raiz quadrada
  ```
  X <sup>2</sub>
  ```
* Define um texto subscrito igual o H<sub>2</sub>O a formula da água.
  ```
  H<sub>2</sub>O
  ```

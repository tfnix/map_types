"Baby<br>
You make my heart beat faster<br>
Baby<br>
You make my heart beat faster<br>
I know"<br>
(The Distillers/Beat Your Heart Out)

## RX - Reactive Programming
***Exemplo basico de uso*** <br>

```js

  /*
   * getInputs()    : InputType[]   
   * inputs$        : String[]
   * 
   */

    this.inputs$ = this.restService.getInputs().pipe(
      map( datas => {
        // Pretty! Modifica o tipo de retorno de getInputs()
        return datas.map(object => object.title)

        
      })

    )
```

Ref: 
https://reactivex.io/documentation/operators/map.html

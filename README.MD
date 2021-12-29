## RX - Reactive Programming
***Exemplo basico de uso*** <br>

```js

  /*
   * getInputs()    : InputType   
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

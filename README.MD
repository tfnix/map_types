"Baby<br>
You make my heart beat faster<br>
Baby<br>
You make my heart beat faster<br>
I know<br>
Let alone to rust alone<br>
Yeah, you're making me<br>
I had to run, the damage is done<br>
Give it up, there, give it up, there's<br>
Nothing left, so take the rest<br>
Yeah, you're draining me<br>
I set it light, it burns so bright<br>
Stab it out, hey, stab it out, hey<br>
...<br>
"<br>
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



Ref: 
https://reactivex.io/documentation/operators/map.html

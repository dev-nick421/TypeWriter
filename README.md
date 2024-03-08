# Vue 3 TypeWriter Component - Drop-In 

Vue 3 Component that simulates typing like this: <br />
![Alt Text](https://github.com/dev-nick421/TypeWriter/blob/main/demo.gif)

Just clone or copy&paste and start using with:
```
<TypeWriter :texts="['TEXT1', 'TEXT2', 'TEXT3']" :eraseDelay="100" :typeDelay="100" :waitTimer="1800" />
```
Delays are customizable. <br /><br />
It shows a blinking cursor by default that can be disabled by changing
```
const showCursor = ref(true); 
```

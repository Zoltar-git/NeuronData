<h1>NeuronData</h1>

<p>An auto-information collecting system in Manyland that stores usernames, bodys, dynamics, items etc.</p>

<h2>How is it used?</h2>

<p>The information that is collected with Neurobot is sent here and then used in another script called Neuron.</p>
<p>A link will be added to Neuron upon it's completion.</p>

```js
let pbd = $.get('https://cdn.jsdelivr.net/gh/Zoltar-git/NeuronData@latest/Items/bodys.txt');
let ppd = $.get('https://cdn.jsdelivr.net/gh/Zoltar-git/NeuronData@latest/Player/players.txt');

setTimeout(()=>{
	bodyData = pbd.responseText;
	playerData = ppd.responseText;
},1000)
```
<p>for use in your own script use the code up above.</p>

<h2>Future updates</h2>

  * Add a section for dynamics and also one for items

<h2>AbieSoft Toast</h2>
<div>Make a simple notification toast for your website.</div>

<h4>Install npm package</h4>
<pre><code>  npm i abiesoft-toast</code></pre>

<h4>Simple use</h4>
<div>add element with id <strong>toasthere</strong> in main page, like this :</div>
<pre><code>  &#60;div id='toasthere'&#62;&#60;/div&#62;</code></pre>
<div>and then for call a notification toast code, like this :</div>
<pre>
<code>
  import {Toast} from 'abiesoft-toast';

    Toast({
         type: 'error',
         message: 'Ops.. Something when wrong',
    }) 
</code>
</pre>

<h4>Toast type</h4>
<div>
    <ul>
        <li>Error</li>
        <li>Success</li>
        <li>Warning</li>
        <li>Info</li>
    </ul>
</div>

<h4>Screenshort</h4>
<img src='error.png' height='55px'> 
<img src='success.png' height='55px'> 
<img src='warning.png' height='55px'> 
<img src='info.png' height='55px'>


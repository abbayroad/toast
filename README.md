<h2>AbieSoft Toast</h2>
<div>Make a simple notification toast for your website.</div>

<h4>Install npm package</h4>
<code>npm i abiesoft-toast</code>

<h4>Simple use</h4>
<div>add element with id <strong>toasthere<strong> in main page, like this :</div>
<pre><code>&#60;div id='toasthere'&#62;&#60;/div&#62;</code></pre>
<div>and then for call a notification toast code, like this :</div>
<pre>
<code>
    import {Toast} from 'abiesoft-toast';

    Toast({
         type: 'error',
         message: 'Ops.. Something when wrong',
    })
</code></pre>
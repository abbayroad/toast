<h2>AbieSoft Toast</h2>
<div>Make a simple notification toast for your website.</div>
<div style='margin-top: 10px; font-weight: bold;'>Install npm package</div>
<div>
<code>npm i abiesoft-toast</code>
</div>

<div style='margin-top: 10px; font-weight: bold;'>Simple use</div>
<div>add with id <strong>toasthere<strong> in main page, like this :</div>
<code><div id='toasthere'></div></code>
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
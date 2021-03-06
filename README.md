## 🔹 Mailchimp Async Form
![Gif](https://i.imgur.com/FV8unDX.gif)

Mailchimp's embedded signup forms open up new tabs. We want users to stay on our site after they click the subscribe button. All you need is your Mailchimp User and List id. Install via npm, import module, initialize with your ids — et voilà. You're done.

### Install
```bash
npm i --save mailchimp-async-form
```

### Use
With Webpack:
```js
import 'mailchimp-async-form';
const mcAsyncForm = mailchimp-async-form('.your-signup-div');
mcAsyncForm({uid, listId});
```


Vanilla:<br/>
Include `mailchimp-async-form.{js,css}`.   
Insert the embedcode into your markup.   
Replace `uid` and `listId` respectively.   
Happiness.   

<br/>
<br/>
   

Licensed under MIT. Very much WIP.

(c) FanMatics, Hamburg

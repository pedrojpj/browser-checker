## Browser Checker
-----

Browser checker allows you to define the compatibility of your website and display an alert screen if it is not compatible.

```
npm install browser-checker --save
```

## Usage

To use add the following tag to your html and define the content you want to use for your incompatibility page:


```html
<div id="browser-check">Your browser is not compatible with this website</div>
```

Define the browsers that are compatible with your website in this way:

```js
    <script>
        var supportSystem = {
            browser: {
                chrome : 70,
                msie : 8,
                firefox: 30,
                safari: 7,
                opera: 8,
                android: true
            },
            system: {
                ios: 6,
                android: 5
            }
        };
    </script>
```

If your browser is not compatible, you will see the message you have defined if it is compatible.




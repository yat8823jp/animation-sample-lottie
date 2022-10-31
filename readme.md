# Lottie animation

- After Effects
- [Bodymovin](https://exchange.adobe.com/apps/cc/12557) After Effects extension
- [Lottie](https://lottiefiles.com/)
- [Lottie-web](https://github.com/airbnb/lottie-web) animation-player

## Usage

1. You need to make animation from After Effects
2. Install Bodymovin and use it
3. export in json file
4. Lottie makes an account and uploads json file from Bodymovin
5. You make html and JavaScript and css

## Help

### Load lottie.js in your html file [GitHub](https://github.com/airbnb/lottie-web/tree/master/build/player)

### 1. You add code ID element on the HMTL file

```
<div id="example"></div>
```

### 2. You add JavaScript file.

Add to this code.
The example.json from Bodymovin.

```
let animationTivel = lottie.loadAnimation( {
    container: document.getElementById( 'example'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: './js/example.json'
} );
```

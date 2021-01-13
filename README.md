# MouseCursorEffects

## Demo
https://h2-won.github.io/HUI/cursorEffect

## How to use

#### 1. Download the files in the Demo.

#### 2. Include the cursor div in the body (HTML).
And specify the color and size of the cursor.

```
<div class="cursor" color="#a29bfe" size="5px"></div>
```

#### 3. Include the stylesheet and script from the demo in your HTML code.
```
<link rel="stylesheet" href="your_some_path/cursorEffect.css">

<script src="your_some_path/cursorEffect.js"></script>
```

#### 4. Use the following cursorEffect() in your HTML or JS.
What can be adjusted is the color, size, thickness, and font size of the text when hovering.

```
<script>

    // cursorEffect(componentClassName, hoverText, hoverColor, hoverSize, hoverThickness, fontSize)

    cursorEffect('demoDiv1');

    cursorEffect('demoDiv2', 'Hello !', '#ffeaa7', '6em', '4px', '1.5rem');

    cursorEffect('demoDiv3', '❤', 'pink', '0', '2.5px', '3rem');

    cursorEffect('someButton', 'Click', 'lightcoral', '3em');

</script>
```

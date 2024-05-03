# Terminal Website
Cool and simple website that looks like a terminal with functional command prompts!
![image](https://github.com/vscimento/terminal/assets/102530346/b15d13e7-adc3-4121-91f5-130004d4aaf7)

## Installation
The website is made with HTML, CSS and Javascript, there's no installation needed, all you need is a browser.

## Creating a command
In the **commands.js** file, add the new command.
```js
new = [
  "<br>",
  "Hello, this is a new command",
  "<br>"
];
```

In the **main.js** file, add the new command.
```js
case "new":
      loopLines(whois, "color2 margin", 80);
      break;
```

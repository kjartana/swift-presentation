# swift-playgrounds

### A short introduction

---

## Tips!

<br>

@fa[arrows gp-tip](Press F to go Fullscreen)

@fa[microphone gp-tip](Press S for Speaker Notes)

---

## Disclaimer

#### My daughter Amalie (10) have written more lines of Swift code than me

- 100 lines and counting :-) |
- We're still at challenge 1: "Learn to Code 1" |

Note:
- Dette er mao en intro til Swift Playgrounds app'en, fra en unges ståsted
- Målet er en kjapp intro til Swift Playgrounds
- Vi har ikke brukt det så mye, mest pga meg
- Challenge 1 består av 46 brett:
-- Commands (6 brett)
-- Functions (7 brett)
-- For loops (7 brett)
-- Conditional (betingelser) code (7 brett)
-- Logical operators (5 brett)
-- While loops (9 brett)
-- Algorithms (5 brett)

---

## Swift

- Programming language by Apple |
- Adopts the best from C and Objective-C |

Note:
- Hørte/leste et sted at en av fordele med Swift var at det ikke var Objective-c :-)
- Swift is statically, strongly typed and uses type inference to determine the initial type of all your variables and constants

---

## Swift Playgrounds

- An iPad app |
- Learning by playing - solving puzzles |
- Instant feedback |
- Introduces and explains the basic coding concepts |

Note:
- App'en har ulike "puzzles" man må løse ved å skrive swift kode
- Man skriver kode og kan kjøre den med det samme for å se resultatet
- Fokuserer på kode kosepter: kommandoer, funksjoner, parametere, løkker, variabler, operatorer, typer, initialisering (Initialization)

---

## Explaining Functions

![Video](https://youtu.be/uKIxWfVBcMU)

---

## Examples

---?image=assets/image/swift-screendump-1.png

Note:
- Screemdumps av oppgaver og kode/løsning

---

## Live coding

Note:
- Video av amalie som løser en oppgave

---

## Lessons learned

- English may be a barrier |
- Easy to get started |
- It's fun! |
- Keep it simple (don't get carried away) |
- "Dad, why should I learn coding?" |
- It "competes" with Netflix, Youtube, games etc

Note:
- Vi har som nevnt ikke brukt det så mye (ref språk barriere)
- Alt er foreløpig på engelsk, det gjør det vanskelig å drive på egenhånd
- Ikke alltid like populært at jeg forsøker å få henne til å lese og forstå oppgaven selv (på engelsk)
- Puzzle/spill konseptet er genialt
- Refaktorering hæ?! "Det funker pappa, hvorfor skal vi endre på det da?"
- Store spørsmål som hva er poenget, hvorfor lære koding, er det gøy?

---

## Template Features

- Code Presenting |
- Repo Source, Static Blocks, GIST |
- Custom CSS Styling |
- Slideshow Background Image |
- Slide-specific Background Images |
- Custom Logo, TOC, and Footnotes |

---?code=sample/go/server.go&lang=golang&title=Golang File

@[1,3-6](Present code found within any repo source file.)
@[8-18](Without ever leaving your slideshow.)
@[19-28](Using GitPitch code-presenting with (optional) annotations.)

---

@title[JavaScript Block]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---?gist=onetapbeyond/494e0fecaf0d6a2aa2acadfb8eb9d6e8&lang=scala&title=Scala GIST

@[23](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](And code-presenting works seamlessly for GIST too, both online and offline.)

---

## Template Help

- [Code Presenting](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Repo Source](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides), [Static Blocks](https://github.com/gitpitch/gitpitch/wiki/Code-Slides), [GIST](https://github.com/gitpitch/gitpitch/wiki/GIST-Slides)
- [Custom CSS Styling](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Slideshow Background Image](https://github.com/gitpitch/gitpitch/wiki/Background-Setting)
- [Slide-specific Background Images](https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting), [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents), and [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---

## Go GitPitch Pro!

<br>
<div class="left">
    <i class="fa fa-user-secret fa-5x" aria-hidden="true"> </i><br>
    <a href="https://gitpitch.com/pro-features" class="pro-link">
    More details here.</a>
</div>
<div class="right">
    <ul>
        <li>Private Repos</li>
        <li>Private URLs</li>
        <li>Password-Protection</li>
        <li>Image Opacity</li>
        <li>SVG Image Support</li>
    </ul>
</div>

---

### Questions?

<br>

@fa[twitter gp-contact](@gitpitch)

@fa[github gp-contact](gitpitch)

@fa[medium gp-contact](@gitpitch)

---?image=assets/image/gitpitch-audience.jpg

@title[Download this Template!]

### <span class="white">Get your presentation started!</span>
### [Download this template @fa[external-link gp-download]](https://gitpitch.com/template/download/sky)

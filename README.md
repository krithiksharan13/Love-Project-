# 💖 A Love Letter

A sweet, animated personal webpage that expresses love and memories, complete with a blooming heart garden animation, custom typography, and a special message from the heart.

This project was built with ❤️ using HTML, CSS, JavaScript, and jQuery.

---

## 🌸 Features

- 🌹 Blooming heart animation with canvas
- ⏱ Countdown timer showing how long you've been together
- ⌨️ Typewriter effect for the message
- 🧠 Personalized love story written in a "code" format
- 🎨 Garden and heart effects using custom scripts and canvas
- 🧑‍🎨 Font Awesome icons and custom digital font

---

---

## 🧠 How It Works

### HTML Highlights (`index.html`)

- The webpage is titled: **"This one is for my Aunty♥"**
- Includes a poetic message written in a stylized "code" format.
- Heart icon (`<i class="fas fa-heart">`) links to a special image.
- A `<canvas>` is used to render the animated heart and garden using JavaScript.
- A digital clock displays how long you've been "together" since **September 22, 2018, 12:57 PM**.

### JavaScript Behavior

```javascript
var offsetX = $("#loveHeart").width() / 2;
var offsetY = $("#loveHeart").height() / 2 - 55;

var together = new Date();
together.setFullYear(2018, 8, 22); // Month is zero-indexed: 8 = September
together.setHours(12);
together.setMinutes(57);
```
1. startHeartAnimation() begins the blooming heart animation.

2. timeElapse(together) continuously updates how long you've been in love.

3. A custom typewriter effect prints the love note like it's being typed.

### 💻 Usage
1. Clone this repository or download the project files.
2. Open index.html in a modern browser (Chrome, Firefox, etc.).
3. Make sure you are connected to the internet (Font Awesome needs it unless hosted locally).
4. Optionally edit the text in index.html to personalize your message.
5. Replace the image.jpg file to the image that you require

### 🛠 Customization
- 💌 Change the love message: Edit the content in the <div id="code"> section.

- ⏳ Change the date/time: Modify the together variable in the <script> block.

- 🎨 Change styles: Edit the CSS in css/default.css.

- 💚 Update the heart image: Replace or rename image.jpg.

### 🌐 Browser Support:
Make sure you're using a browser that supports HTML5 canvas.

- ✅ Chrome 14+
- ✅ Firefox 7+
- ✅ Safari 4+
- ✅ Edge/IE 9+

If canvas isn’t supported, a graceful fallback message will appear.

### ❤️ Credits
- 🌸 Heart animation inspired by classic canvas garden effects

- 🧠 jQuery for animations and DOM manipulation

- 🎨 Font Awesome for icons

- 💾 Digital-7 Mono Font used for the clock

### 👋 Final Words
This is a personal project made with love. Whether you're a developer, a designer, or just someone looking to express your feelings in a unique way, feel free to adapt this project for your own story.

I LOVE YOU SO MUCH, Shwe♥

– Your IDIOT

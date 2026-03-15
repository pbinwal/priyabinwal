---
layout: page
title: Contact
permalink: /contact/
---

<style>
  /* Remove main card background */
  main {
    background-color: transparent !important;
  }
</style>
<link rel="stylesheet" href="{{ '/assets/css/handwritten.css' | relative_url }}">

<!-- Page container -->
<div class="straight-border" style="background-color: transparent; color: #000000; padding: 50px 20px; font-family: 'EB Garamond', Georgia, serif; font-size: 21px; max-width: 900px; margin: 40px auto; border-radius: 0px; border: none; position: relative;">
<div style="position: relative; z-index: 1;">

  <!-- Photo -->
<div style="text-align: center; margin-bottom: 30px;">
  <img src="{{ '/assets/images/PB_photo.jpg' | relative_url }}"
       alt="Profile Photo"
       loading="lazy"
       style="width: 220px; height: auto; border-radius: 12px;">
</div>


<!-- Email -->
  <p id="greeting" style="text-align: center; font-size: 28px; color: #48474c; margin-bottom: 10px; font-weight: bold; transition: all 0.3s; font-family: 'Chathura', sans-serif;">
    <span id="hello-word" style="color: #cbc104ff; font-family: 'Chathura', sans-serif; font-size: 1.6em;">Hello</span>
    <span style="font-family: 'Chathura', sans-serif; font-size: 1.6em; margin-left: 0.5em;">fellow human!</span>
  </p>
  <script>
    const greetings = [
    'Hello',
    'Namaskaram',
    'Hola',
    'Bonjour',
    'Ciao',
    'Hallo',
    'Olá',
    'Привет',
    '你好',
    'こんにちは',
    '안녕하세요',
    'مرحبا',
    'שלום',
    'Shalom',
    'ਸਤਿ ਸ੍ਰੀ ਅਕਾਲ',
    'สวัสดี',
    'Xin chào',
    'Hei',
    'Hej',
    'Ahoj',
    'Γειά σου',
    'Selam',
    'Merhaba',
    'Sawubona',
    'Salam',
    'Szia',
    'Sveiki',
    'Tere',
    'Halo',
    'Mingalaba',
    'Kamusta',
    'Salve',
    'Dzień dobry',
    'God dag',
    'Dia dhuit',
    'Aloha',
    'Sannu',
    'Habari',
    'Jambo',
    'Bula',
    'Malo e lelei',
    'Talofa',
    'Kia ora',
    'Sain baina uu',
    'Saluton',
    'Zdravo',
    'Pozdrav',
    'Moien',
    'Terve',
    'Labas',
    'Dobrý den',
    'Cześć',
    'Bok',
    'Dobar dan'
  ];

    const helloWord = document.getElementById('hello-word');
    let greetIndex = 0;
    helloWord.textContent = greetings[0];
    setInterval(() => {
      greetIndex = (greetIndex + 1) % greetings.length;
      helloWord.textContent = greetings[greetIndex];
    }, 700);
  </script>
  <!-- Intro -->
  <p class="handwritten" style="text-align: center;">
    I am a PhD student at the Institute for Neurobiology, University of Tuebingen, Germany.<br>
    Drop me a message and I'll write back!
  </p>

  <!-- Contact Form -->
  <form action="https://formspree.io/f/xbdzawpj" method="POST" style="max-width: 560px; margin: 30px auto 0; font-family: 'EB Garamond', Georgia, serif;">

    <div style="margin-bottom: 18px;">
      <label style="display: block; font-size: 0.95em; color: #48474c; margin-bottom: 6px;">Your name</label>
      <input type="text" name="name" required
        style="width: 100%; padding: 10px 14px; border: 1px solid #cccccc; border-radius: 4px; font-family: 'EB Garamond', Georgia, serif; font-size: 1em; background: rgba(255,255,255,0.7); box-sizing: border-box;">
    </div>

    <div style="margin-bottom: 18px;">
      <label style="display: block; font-size: 0.95em; color: #48474c; margin-bottom: 6px;">Your email</label>
      <input type="email" name="email" required
        style="width: 100%; padding: 10px 14px; border: 1px solid #cccccc; border-radius: 4px; font-family: 'EB Garamond', Georgia, serif; font-size: 1em; background: rgba(255,255,255,0.7); box-sizing: border-box;">
    </div>

    <div style="margin-bottom: 24px;">
      <label style="display: block; font-size: 0.95em; color: #48474c; margin-bottom: 6px;">Message</label>
      <textarea name="message" rows="6" required
        style="width: 100%; padding: 10px 14px; border: 1px solid #cccccc; border-radius: 4px; font-family: 'EB Garamond', Georgia, serif; font-size: 1em; background: rgba(255,255,255,0.7); resize: vertical; box-sizing: border-box;"></textarea>
    </div>

    <div style="text-align: center;">
      <button type="submit"
        style="background-color: #3a9a8f; color: #ffffff; border: none; padding: 12px 36px; font-family: 'Chathura', sans-serif; font-size: 1.1em; border-radius: 4px; cursor: pointer; letter-spacing: 0.05em;">
        Send
      </button>
    </div>

  </form>

</div>
</div>

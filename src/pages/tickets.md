---
layout: ../layouts/MarkdownLayout.astro
title: Билеты
---

**Мы пока маленькие и не раскрученные, у нас нет юрлица, поэтому мы проводим конфу под эгидой встречи друзей, где все скидываются на аренду дома и еду. Деньги можно закинуть нашим оргам:**

## Катя

<p>
  Мне можно перевести за билет на PayPal по мейлу 
  <span style="display: inline-flex; align-items: center; gap: 0.3rem; position: relative;">
    <strong id="paypalEmail">kaitherinaturkey@gmail.com</strong>
    <button 
      onclick="copyEmail()" 
      title="Скопировать"
      style="background: none; border: none; cursor: pointer; font-size: 1rem;">
      📋
    </button>
    <span id="copyNotice" 
          style="position: absolute; top: -1em; left: 15em; font-size: 0.8rem; opacity: 0; transition: opacity 0.3s ease;">
      copied!
    </span>
  </span>
  или <a href="http://paypal.me/kaitherina">напрямую.</a>
</p>

<script>
  function copyEmail() {
    const email = document.getElementById("paypalEmail").textContent;
    navigator.clipboard.writeText(email).then(() => {
      const notice = document.getElementById("copyNotice");
      notice.style.opacity = "1";
      setTimeout(() => {
        notice.style.opacity = "0";
      }, 1200);
    });
  }
</script>

<p>
  Из доступных банков у меня есть:
  <ul>
    <li><strong><a href="http://revolut.me/katef20">Revolut</a></strong></li>
    <li><strong><a href="https://t.me/Kaitherina">N26</a></strong></li>
    <li><strong><a href="https://t.me/Kaitherina">Sparkasse</a></strong></li>
  </ul>
</p>

<p>
  Могу прислать IBAN любого из них в личку, напиши мне в <a href="https://t.me/Kaitherina">телеге.</a>

Eщё всегда есть вариант перевести на криптокошелёк или отдать наличкой.
</p>

---

## Тимур

- У меня тоже есть [револют](http://revolut.me/noob001)
- Но если ты предпочитаешь классические переводы, напиши мне в [телеге,](http://t.me/noob001) и я дам все контакты. Я на авто и весьма мобильный по Берлину, так что мы найдём как пересечься.


---

И заполни, пожалуйста, эту [форму.](https://docs.google.com/forms/d/e/1FAIpQLScWK72kPNWntwmy2qJfQtXpVfxv08GAzLCr2s8yNGI6nruaZg/viewform?pli=1) Эта информация — исключительно для более точной организации конфы. Спасибо!

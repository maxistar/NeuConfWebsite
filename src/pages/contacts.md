---
layout: ../layouts/MarkdownLayout.astro
title: Контакты
---

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
  или<a href="http://paypal.me/kaitherina">напрямую.</a>
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
  Из доступных банков у меня есть<a href="http://revolut.me/katef20">Revolut,</a>N26 и Sparkasse, 
напиши мне личное сообщение<a href="https://t.me/Kaitherina">в телеге</a>и я скину реквизиты. 
Eщё всегда есть вариант перевести на криптокошелёк или отдать наличкой.
</p>

---

## Тимур

- У меня тоже есть[револют](http://revolut.me/noob001)
- Но если ты предпочитаешь классические переводы, напиши мне в[телеге,](http://t.me/noob001)и я дам все контакты. Я на авто и весьма мобильный по Берлину, так что мы найдём как пересечься.




[**Купить билеты**](/tickets/)

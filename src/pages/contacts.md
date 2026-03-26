---
layout: ../layouts/MarkdownLayout.astro
title: Контакты
---

## Катя

<p>
  Я всегда на связи <a href="https://t.me/Kaitherina">в телеге</a>или<a href="https://instagram.com/kaithymi">в инсте.</a> Ну и для пущей серьёзности добавлю мейл 
  <span style="display: inline-flex; align-items: center; gap: 0.3rem; position: relative;">
    <strong
      id="paypalEmail"
      onclick="copyEmail()"
      title="Скопировать email"
      style="cursor: pointer;"
    >kaitherinayrd@gmail.com</strong>
    <span id="copyNotice" 
          style="position: absolute; top: -1em; left: 15em; font-size: 0.8rem; opacity: 0; transition: opacity 0.3s ease;">
      copied!
    </span>
  </span>
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

---

## Тимур
Напиши мне в[телеге,](http://t.me/noob001)и я дам ответы на все вопросы.


----
## соцсети
А ещё у нас есть всякие соцсети, подписывайся на нас<a href="https://instagram.com/neuconf_berlin">в инсте</a>и залетай в чатик<a href="https://t.me/neuconf">в телеге.</a>


----

[**Присоединиться**](/participate/)

<style>
  hr {
    border: 0;
    border-top: 1px solid #BFD88D;
    margin: 1.5rem 0;
  }
</style>

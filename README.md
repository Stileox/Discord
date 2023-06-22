# Kurulum;
- *__Öncelikle Discord Hesabı Oluşturun!__*

### Sunuculara Katıl;
```text
https://discord.gg/CJHrAF4nq4 //gifaura
https://discord.gg/kVQVCy75YK // Game Trust j4j
https://discord.gg/zpU5Nv9X8n
https://discord.gg/z5jYcxsHYe
https://discord.gg/4ptsFyS
https://discord.gg/j4j
https://discord.gg/BBt8jVMSpr
https://discord.com/invite/BDH4MvzF2C
```

- *__CTRL + SHIFT + I Tuşuna Basıp Console Sekmesine Gelin!__*
- *__Konsol' a Bunu Yapıştır;__*
```javascript
window.webpackChunkdiscord_app.push([
  [Math.random()],
  {},
  req => {
    for (const m of Object.keys(req.c)
      .map(x => req.c[x].exports)
      .filter(x => x)) {
      if (m.default && m.default.getToken !== undefined) {
        return copy(m.default.getToken());
      }
      if (m.getToken !== undefined) {
        return copy(m.getToken());
      }
    }
  },
]);
console.log('%cWorked!', 'font-size: 50px');
console.log(`%cYou now have your token in the clipboard!`, 'font-size: 16px');
```
- *__Token Panoya Kopyalandı!__*

### Adımları Takip Et;
- *__config Dosyasını düzenle__*
```
tokens: ["Yapıştır"]
```
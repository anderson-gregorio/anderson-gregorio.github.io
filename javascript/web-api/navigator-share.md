# Navigator Share

O método navigator.share() da API de compartilhamento da Web chama o mecanismo de compartilhamento nativo do dispositivo.

```javascript
const shareData = {
  title: 'MDN',
  text: 'Aprenda desenvolvimento web no MDN!',
  url: 'https://developer.mozilla.org',
}

const btn = document.querySelector('button');
const resultPara = document.querySelector('.result');

// Deve ser acionado algum tipo de "ativação do usuário"
btn.addEventListener('click', async () => {
  try {
    await navigator.share(shareData)
  } catch (err) {
    resultPara.textContent = 'Error: ' + e
  }
  resultPara.textContent = 'MDN compartilhado com sucesso!'
});
```

[https://developer.mozilla.org/pt-BR/docs/Web/API/Navigator/share](https://developer.mozilla.org/pt-BR/docs/Web/API/Navigator/share)
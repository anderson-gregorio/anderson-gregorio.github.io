# Network Information

A NetworkInformationinterface fornece informações sobre a conexão que um dispositivo está usando para se comunicar com a rede e fornece um meio para que os scripts sejam notificados se o tipo de conexão for alterado

```javascript
var connection = navigator.connection || navigator.mozConnection || navigator.webkitConnection;

function updateConnectionStatus() {
  const velocidade = document.getElementById("velocidade")
  console.log(velocidade);

  if (velocidade) {
    velocidade.innerText = connection.downlink.toString();
  }
}

connection.addEventListener("change", updateConnectionStatus);
updateConnectionStatus();
```

[https://developer.mozilla.org/en-US/docs/Web/API/NetworkInformation](https://developer.mozilla.org/en-US/docs/Web/API/NetworkInformation)
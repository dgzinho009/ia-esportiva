<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>IA Esportiva - Acesso</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f2f2f2; text-align: center; padding: 40px; }
    .container { background: #fff; padding: 30px; border-radius: 12px; box-shadow: 0 0 15px rgba(0,0,0,0.1); display: inline-block; }
    button { padding: 10px 20px; font-size: 16px; border: none; border-radius: 8px; cursor: pointer; }
    #confirmar { display: none; margin-top: 20px; background: #25d366; color: white; }
    #pagar { background: #ff9900; color: white; }
  </style>
</head>
<body>
  <div class="container">
    <h2>Adquira o acesso à IA Esportiva</h2>
    <p>Valor: <strong>R$ 6,90</strong></p><button id="pagar" onclick="mostrarConfirmar()">Realizar Pagamento (PIX)</button>

<div id="confirmar">
  <p>Após o pagamento, clique abaixo para confirmar:</p>
  <a href="https://wa.me/5565996886741?text=Oi%2C+j%C3%A1+realizei+o+pagamento+de+R%24+6%2C90+e+quero+acesso+%C3%A0+IA+Esportiva" target="_blank">
    <button>Confirmar Pagamento via WhatsApp</button>
  </a>
</div>

  </div>  <script>
    function mostrarConfirmar() {
      setTimeout(() => {
        document.getElementById('confirmar').style.display = 'block';
      }, 2000); // espera 2 segundos pra simular o pagamento
    }
  </script></body>
</html>

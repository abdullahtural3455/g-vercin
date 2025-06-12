<div class="ihale-karti">
  <img src="guvercin.jpg" alt="Martis" style="width:100%">
  <div class="etiket" id="sayac">00:00:00</div>
  <h3>TR-24-22-1205 MARTİS</h3>
  <p>Son Teklif: <strong>10.200₺</strong></p>
  <p>Teklif Veren: <strong>1 Kişi</strong></p>
  <button>Teklif Ver</button>
</div>

<script>
  // Geri sayım örneği - 24 saat sonrası için
  let countDownDate = new Date().getTime() + 24*60*60*1000;

  let x = setInterval(function() {
    let now = new Date().getTime();
    let distance = countDownDate - now;

    if (distance < 0) {
      clearInterval(x);
      document.getElementById("sayac").innerHTML = "Süresi Doldu";
      return;
    }

    let hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    let minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    let seconds = Math.floor((distance % (1000 * 60)) / 1000);

    document.getElementById("sayac").innerHTML = ${hours}sa ${minutes}dk ${seconds}sn;
  }, 1000);
</script>
30 tane ihale


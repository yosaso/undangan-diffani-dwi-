# undangan-diffani-dwi-
Resepsi pernikahan
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Undangan Pernikahan Diffani & Dwi</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: #f9f9f9;
    color: #333;
    text-align: center;
}
.container {
    padding: 30px 20px;
}
h1, h2 {
    font-weight: 600;
}
.card {
    background: #ffffff;
    border-radius: 16px;
    padding: 25px;
    margin: 20px auto;
    max-width: 420px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.08);
}
.btn {
    display: inline-block;
    padding: 12px 20px;
    background: #222;
    color: #fff;
    text-decoration: none;
    border-radius: 25px;
    margin-top: 10px;
}
.small {
    font-size: 14px;
    color: #666;
}
audio {
    display: none;
}
</style>
</head>

<body>

<audio autoplay loop>
  <source src="https://cdn.pixabay.com/download/audio/2022/03/15/audio_2bfb07c3b2.mp3" type="audio/mpeg">
</audio>

<div class="container">

<div class="card">
<h2>💍 Undangan Pernikahan</h2>
<p class="small">Assalamu’alaikum Warahmatullahi Wabarakatuh</p>
</div>

<div class="card">
<h1>Diffani Achmadi S.</h1>
<h2>&</h2>
<h1>Dwi Kuckitasari</h1>
<p class="small">Putri dari Bapak Yetno</p>
</div>

<div class="card">
<h2>📅 Waktu Acara</h2>
<p><b>Senin, 30 Desember</b></p>
<p>Pukul: Rileks / Selesai</p>
</div>

<div class="card">
<h2>📍 Lokasi Acara</h2>
<p>Desa Keniten, Dusun Mbesuk<br>
Kec. Mojo, Kab. Kediri</p>
<a class="btn" href="https://maps.google.com/?q=Desa+Keniten+Dusun+Mbesuk+Mojo+Kediri" target="_blank">
📍 Buka Google Maps
</a>
</div>

<div class="card">
<h2>⏳ Hitung Mundur</h2>
<p id="countdown"></p>
</div>

<div class="card">
<h2>💌 Konfirmasi Kehadiran</h2>
<a class="btn" href="https://wa.me/62XXXXXXXXX?text=Assalamualaikum%2C+saya+akan+hadir+di+acara+pernikahan+Diffani+%26+Dwi" target="_blank">
📲 RSVP WhatsApp
</a>
</div>

<div class="card">
<h2>🎁 Amplop Digital</h2>
<p>BCA<br>
<b>1401575591</b><br>
a.n. Diffani Achmadi S.</p>
</div>

<div class="card">
<p class="small">
Merupakan suatu kehormatan dan kebahagiaan bagi kami  
apabila Bapak/Ibu/Saudara/i berkenan hadir dan memberikan doa restu.
</p>
<p><b>Wassalamu’alaikum Warahmatullahi Wabarakatuh</b></p>
</div>

</div>

<script>
const eventDate = new Date("December 30, 2025 08:00:00").getTime();
const timer = setInterval(function() {
    const now = new Date().getTime();
    const distance = eventDate - now;

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));

    document.getElementById("countdown").innerHTML =
        days + " Hari " + hours + " Jam " + minutes + " Menit ";

    if (distance < 0) {
        clearInterval(timer);
        document.getElementById("countdown").innerHTML = "Acara Sedang Berlangsung";
    }
}, 1000);
</script>

</body>
</html>

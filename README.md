<html><meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400;700&display=swap" rel="stylesheet"><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script><link href="https://drive.google.com/uc?export=view&id=1yFuxnd1AqPeAqwJCx99HADz64UKMLgw4" rel="stylesheet" type="text/css" /><script src="https://hbd.htmlku.repl.co/script.js"></script>
<head>
<!-- Edit Judul Script di Sini -->
  <title>HBD</title>
<!-- 
  Made with love by Rayys!

     Blog: well
     Instagram: agustinusadikristanto
     TikTok: agustinusadikristanto
     Email: agustinusadikristanto@gmail.com

  Thanks to all <3
-->
</head>
<style>
:root {
--warna-bg: rgba(0, 0, 0, .7); 
--warna-teks: white;
--bingkai: 14px;
--gaya-font: 'Josefin Sans', sans-serif;
}
</style>
<body><div id="bodyblur"><img id="wallpaper" src="" width="100%" height="100%"/><div id="beneranblur"></div></div>

<div id='Content'>

<div><marquee id="imglewat" direction="right"><img id="fotonimasi" src="" width="100px" height="100px"/></marquee></div>

<div><div id='pergeseran'>

<!-- Pesan -->
<p><b><img src="https://i.ibb.co/s9cTyc0/bunga.gif"/><br>
	<span>Halooo Nisaaa </span>
</b></p>

<p><b><img src="https://feeldreams.github.io/cilukba.gif"/><br>
	<span> Cieee yg hari ini ultah </span>
</b></p>

<p><b><img src="https://feeldreams.github.io/g5.gif"/><br>
	<span>!!HAPPY BIRTHYDAY!! </span>
</b></p>

<p><b><img src="https://feeldreams.github.io/mndkat.gif"/><br>
	<span>Semoga Panjang Umur Dan Sehat Selalu </span>
</b></p>

<p><b><img src="https://feeldreams.github.io/gumush.gif"/><br>
	<span>Aku Cuma Pengen Kamu Sehat Selalu </span>
</b></p>

<!-- Tombol Akhir --><p><b><img id="fotolove" src="https://i.postimg.cc/CLsvGn2v/pngwing-com-4.png" onClick="akhiran();"/><br>
	<span>Oh iya, coba klik gambar nya...</span>
</b></p>

</div></div>
<p id="idgeser">Geser ke kanan yaa... &#128073;</p><p id="idkalimat"></p><p id="idmarq"><marquee id="palingakhir"></marquee></p>

<!-- Tombol Kirim Pesan --><div id="contTom"><a class='button' onClick="sjawab()">Kirim Pesan</a></div>
</div>

<script>
  function nongeser() {idgeser.style = "transform: scale(.1);opacity:0";fotolove.style="opacity:1;visibility:visible";}
  function showDiv() {setTimeout(kpemb,100);setTimeout(nongeser,2500);document.getElementById('Content').style = "opacity:1;margin-top:10vh;animation:none 3s infinite;";document.getElementById("pergeseran").style = "opacity:1;visibility:visible;";}
  function showAkhir() {setInterval(createHeart,200);document.getElementById('k2').style = "opacity:1;transform:scale(1);margin:0;";document.getElementById('Content').style.display = "none";}
  function mulaiakhir() {nonDiv();setTimeout(showAkhir,500);setTimeout(finalis,600);}
  function tombol(){contTom.style="margin-top:20px;opacity:1;transform: scale(1);";ftom=1;} ftom=0; function sjawab(){if(ftom==1){jawab();}}
  var aa=0,pemb;pemb = "";var i=0,halo;halo = "";var u=0,text2;text2 = "";var o=0,text3;text3 = "";var a=0,final1;final1 = "";var ab=0,final2;final2 = "";
  function kpemb() {document.getElementById('bodyblur').style = "opacity:.7;";}
  function finalis() {document.getElementById("bq").style = "opacity:1;visibility:visible;margin-top:0";setTimeout(showTom,4000);}
  const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040',}); const swalsy = Swal.mixin({confirmButtonText: 'Iya', allowOutsideClick: false,}); const swalst = Swal.mixin({allowOutsideClick: false, showConfirmButton: false, timer: 1000, timerProgressBar: true, didOpen: () => {Swal.showLoading();const b = Swal.getHtmlContainer().querySelector('b');timerInterval = setInterval(() => {Swal.getTimerLeft()}, 100)},willClose: () => {clearInterval(timerInterval)}}); const style = document.createElement('style');
  function play() {var audio = new Audio('' + linkmp3);audio.play();} const body = document.querySelector("body");function createHeart() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);
  function StartMarqueeL(){imglewat.style="opacity:1;height:100px;";var marquee = document.getElementById ("imglewat");marquee.start();}function StopMarqueeL(){var marquee = document.getElementById ("imglewat");marquee.stop();}StopMarqueeL(); function akhiran(){setTimeout(startmq,4000);bodyblur.style="opacity:.4;animation:none";beneranblur.style="-webkit-backdrop-filter:blur(5px); backdrop-filter:blur(5px)";wallpaper.style="transform: scale(1.6)";pergeseran.style="display:none";StartMarqueeL();idgeser.innerHTML = "";idkalimat.innerHTML = akhirkata2;idgeser.style = "opacity:1;transform: scale(1);font-size:16px;font-weight:400;margin:0 30px;margin-top:15px;";setTimeout(aksiakhir,800);}
  function startmq(){var marquee = document.getElementById ("palingakhir");marquee.start();}function stopmq(){var marquee = document.getElementById ("palingakhir");marquee.stop();}stopmq();
  async function menuju(){await swals.fire('OK!', 'Kirim pesan ke WhatsApp aku, ya!', 'success');window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;}
  var aa=0,akhirkata;akhirkata = "";function aksiakhir() {if(aa<akhirkata.length){idgeser.innerHTML += akhirkata.charAt(aa);aa++;setTimeout(aksiakhir,65);}
    if(aa==akhirkata.length){idkalimat.style = "opacity:1;transform: scale(1);font-size:16px;margin-top:20px";setTimeout(showpalingakhir,1100);}
   } function showpalingakhir(){palingakhir.style = "opacity:1;transform: scale(1);font-size:16px;margin-top:20px";setTimeout(tombol,4000);}
</script>

<script type="text/javascript">
       async function jawab(){
           var { value: jawaban } = await swals.fire({
               title: 'Isi Pesan Kamu', input: 'text', allowOutsideClick: false, showCancelButton: false,
           });
           if(jawaban && jawaban.length < 16){
           	window.jawaban = jawaban;pesanwhatsapp = jawaban;menuju(085640294349);
           } else {
               await swals.fire('Ups!', 'Kolom tidak boleh kosong atau lebih dari 15 karakter, ya!');
           }
       }
        
       async function pertama(){
       	 wallpaper.src = "https://feeldreams.github.io/wpjalanan.jpg";
            fotonimasi.src = "https://i.postimg.cc/KjgMkqbH/d186d40026c605b289fa1b062d112df4.gif";
       	 audio = new Audio('');
       
            akhirkata = "Semoga di hari spesialmu ini, kamu menjadi pribadi yang lebih baik yaaa, semangat terus ngejalanin hari haru mu, maaf yah kalau selama ini aku terkesan cuek ke kamu... aku minta maaf kalau aku gabisa selalu ada buat kamu, semangat yah aku bakalan ngedukung kamu terus kok... selamat ulang tahun ya nisa, cie yg udah tua wkwkwk... kalau kamu butuh bantuan aku bilang aja gapapa, selagi aku bisa bantu aku bakalan usaha buat bantu kamu... aku juga ga masalah kalau kamu udah punya incaran baru atau kamu mau sama yg lain... aku cuma mau yg terbaik buat kamu, aku sadar diri kok... btw akhir akhir ini sikap kamu jadi cuek banget yah... ya aku tau sih itu karna kesalahan aku juga, maaf yah aku banyak salah sama kamu... bahkan sampe sekarang aja aku masih blm bisa jadi sosok yg baik buat kamu... btw akhir akhir ini aku juga banyak kerjaan... semenjak aku magang aku sering kelelahan sikap ku jadi lebih ga beres, aku juga ga tau kenapa aku kek gini..., ya meskipun aku kadang terkesan cuek ga peduli sama kamu tapi aku sering kepikiran kamu gimana... kmu di sana aman aman aja kan? jahga diri baik baik yah... aku juga kadang suka kepikiran ngeliat pp mu yg berubah kek gitu vibes pemandangan dll aku sebenarnya suka ovt, ya aku tau aku bukan siapa siapa kamu... tapi ya... aku juga gatau sih aku kenapa, ya yaudah intinya jaga diri baik baik yah. maaf yah aku blm bisa ngasih apa apa ke kamu, website ini aku buat jam 8 malam ini lho hehehe... aku ga jago bikin kata kata ucapan buat orang ya mungkin aku nulis sesuai apa yang ada di fikiran aku aja. sorry...      ";
            akhirkata2 = "Happy Birthday!!!";
            palingakhir.innerHTML = "Semangat Yah Manis ";
            
            await swalst.fire('Tunggu');lanjut();
        }
        pertama();
        
        async function lanjut() {
        	await swals.fire('Selamat datang!', 'Sekarang lihat ini ya :)');showDiv();audio.play();
        }
</script>
</body>
</html>

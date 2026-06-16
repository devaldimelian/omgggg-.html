<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta name="description" content="@feelthisray - Script HTML by Feeldream Repl Co">
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1" />
    <title>🩵✨  — HTML Lirik Lagu</title>
    <link href="https://fonts.googleapis.com/css2?family=Handlee&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Patrick+Hand&family=Sriracha&family=Itim&display=swap" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css2?family=Berkshire+Swash&display=swap" rel="stylesheet">
	<script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script>
    <style>
        :root {
            /* Tema Biru Elegan */
            --color-env: #90e0ef;
            --color-env2: #00b4d8;
            --color-flap: #0077b6;
            --color-bg: #03045e;
            --color-heart: #3a86ff;
            --color-sparkle: #fff;
        }
        
        body {background: black;font-family:"Sriracha",serif;overflow:hidden;margin:0;padding:0;user-select:none;-webkit-user-select:none;}
        
        #bodyblur{opacity:.3;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.5);transition:all 1s ease;z-index: 1;}
        #wallpaper{width:100%;height:100%;transform:scale(2);transition:all 1.3s ease;object-fit: cover;}

        /* HALAMAN 1: OVERLAY START */
        .overlay{position:fixed;top:0;left:0;width:100%;height:100%;display:flex;justify-content:center;align-items:center;background:rgba(0,0,0,1);z-index:9999;transition: all 0.6s ease;}
        .cover{color:white;margin-top:-180px;display:flex;flex-direction:column;justify-content:center;align-items:center}
        .cover p{font-size:17px;font-weight:700;}
        .awalan{margin-top:20px;width:250px;min-height:25px;padding:12px;font-size:13px;color:white;background:rgba(0,119,182,0.3);border:1px solid #90e0ef;border-radius:20px;display:flex;align-items:center;text-align:left;cursor:pointer;transition: all 0.3s;}
        .awalan:hover {background: rgba(0,119,182,0.6); transform: scale(1.05);}
        .awalan svg{margin-right:15px;width:25px;height:25px;stroke:#90e0ef}

        /* HALAMAN 2: ENVELOPE (AMPLOP) */
        .envlope-wrapper{position: absolute; top: 40%; left: 50%; transform: translate(-50%, -50%); height:210px; z-index: 10; display: none; flex-direction: column; align-items: center; transition: all 0.6s ease;} 
        #envelope{position:relative;width:160px;height:110px;border-bottom-left-radius:6px;border-bottom-right-radius:6px;background-color:var(--color-flap);box-shadow:0 4px 20px rgba(0,0,0,.2); cursor: pointer;} 
		.front{position:absolute;width:0;height:0;z-index:3} 
		.flap{border-left:80px solid transparent;border-right:80px solid transparent;border-bottom:55px solid transparent;border-top:55px solid var(--color-flap);transform-origin:top;pointer-events:none} 
		.pocket{border-left:80px solid var(--color-env);border-right:80px solid var(--color-env);border-bottom:55px solid var(--color-env2);border-top:55px solid transparent;border-bottom-left-radius:6px;border-bottom-right-radius:6px} 
		
        /* Kertas Surat */
        .letter{position:relative;background-color:#f0f8ff;width:90%;margin:0 auto;height:95%;top:5%;border-radius:6px;box-shadow:0 2px 26px rgba(0,0,0,.08);padding:10px;box-sizing:border-box} 
		.letter:after{content:'';position:absolute;top:0;bottom:0;left:0;right:0;background-image:linear-gradient(180deg,rgba(255,255,255,0) 25%,rgba(144,224,239,.4) 55%,rgba(144,224,239,.8) 100%); z-index: 3; pointer-events: none;} 
		.message{position:relative;z-index:4;font-family:'Handlee',cursive;color:#0077b6;text-align:center;line-height:1;} 
		.message p{margin:5px 0;font-size:1.1em;} 
		
        /* Foto boneka di dalam surat */
        .boneka-surat {position: absolute; bottom: -2px; right: -2px; width: 55px; height: auto; z-index: 5; mix-blend-mode: multiply;}

        .open .flap{transform:rotateX(180deg);transition:transform .4s ease,z-index .6s;z-index:1} 
		.close .flap{transform:rotateX(0deg);transition:transform .4s .6s ease,z-index 1s;z-index:5} 
		.close .letter{transform:translateY(0);transition:transform .4s ease,z-index 1s;z-index:1} 
		.open .letter{transform:translateY(-55px) rotate(-2deg);transition:transform .4s .2s ease,z-index .6s;z-index:2} 
		
        /* SISTEM ELEMEN PETASAN MELETUS */
        .firework-particle {
            position: fixed;
            pointer-events: none;
            z-index: 9999;
            width: 45px;
            height: auto;
            object-fit: contain;
            animation: explode 1.2s cubic-bezier(0.1, 0.8, 0.3, 1) forwards;
        }
        .firework-particle.text-iloveyou {
            width: 75px;
            mix-blend-mode: screen;
        }
        .firework-particle.emoji {
            width: auto;
            height: auto;
            font-size: 28px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        @keyframes explode {
            0% {
                transform: translate(-50%, -50%) scale(0.3) rotate(0deg);
                opacity: 1;
            }
            80% {
                opacity: 1;
            }
            100% {
                transform: translate(var(--x), var(--y)) scale(1.1) rotate(var(--r));
                opacity: 0;
            }
        }

        .reset {margin-top: 30px; text-align: center;}
        .reset button {font-family:"Sriracha",serif;font-weight: 600;transition: all 0.3s ease;background-color: var(--color-env2);border: 2px solid var(--color-env2);border-radius: 20px;color: white;padding: 6px 14px;font-size: 16px;box-shadow: 0 5px 20px rgba(0,0,0,0.15); cursor: pointer;}
        .reset button:hover {background-color: var(--color-flap); border-color: var(--color-flap); transform: scale(1.05);}

        /* HALAMAN 3: HALAMAN MINTA MAAF */
        .halaman-maaf {position: fixed; top: 0; left: 0; width: 100%; height: 100%; display: none; flex-direction: column; justify-content: center; align-items: center; z-index: 20; color: white; padding: 20px; box-sizing: border-box;}
        .box-maaf {background: rgba(0, 119, 182, 0.25); border: 1px solid rgba(144, 224, 239, 0.4); backdrop-filter: blur(10px); padding: 25px; border-radius: 20px; width: 85%; max-width: 400px; text-align: center; box-shadow: 0 10px 30px rgba(0,0,0,0.4); font-family: "Itim", cursive;}
        .box-maaf p {font-size: 19px; line-height: 1.5em; color: #fff; margin-bottom: 25px; font-weight: bold; min-height: 40px;}
        .btn-next {font-family: "Sriracha", serif; background: var(--color-env2); border: none; padding: 10px 20px; border-radius: 20px; color: white; font-size: 16px; cursor: pointer; transition: all 0.3s;}
        .btn-next:hover {background: var(--color-flap); transform: scale(1.05);}

        /* HALAMAN 4: SCREEN SINKRONISASI FOTO 1 PER 1 & ZOOM IN */
        .halaman-galeri {position: fixed; top: 0; left: 0; width: 100%; height: 100%; display: none; flex-direction: column; justify-content: center; align-items: center; z-index: 30;}
        .photo-container {position: relative; width: 260px; height: 340px; border: 5px solid #fff; border-radius: 15px; overflow: hidden; box-shadow: 0 10px 25px rgba(0,0,0,0.5); background: #222;}
        
        /* Animasi khusus Zoom-In Halus saat foto aktif */
        .slide-photo {position: absolute; top:0; left:0; width: 100%; height: 100%; object-fit: cover; opacity: 0; transform: scale(1); transition: opacity 0.8s ease, transform 6s cubic-bezier(0.25, 0.46, 0.45, 0.94) forwards;}
        .slide-photo.active {opacity: 1; transform: scale(1.15);}
        
        /* Wadah Lirik dan Terjemahan Indonesia */
        .lirik-container {margin-top: 25px; width: 85%; min-height: 90px; text-align: center; z-index: 35;}
        .lirik-text {font-family: "Itim", cursive; font-size: 19px; color: #fff; line-height: 1.4em; text-shadow: 0 2px 4px rgba(0,0,0,0.8); margin: 0;}
        .terjemahan-text {font-family: "Itim", cursive; font-size: 14px; color: #90e0ef; font-style: italic; margin-top: 8px; line-height: 1.3em; text-shadow: 0 1px 3px rgba(0,0,0,0.8);}

        /* STIKER */
        .stiker{margin-top:-390px; position:absolute; display:none; justify-content:center; align-items:center; z-index:999;}
        .stiker img{width:75px;height:75px;box-shadow:0 4px 30px rgba(0,180,216,0.4);backdrop-filter:blur(5px);background:rgba(255,255,255,0.6);border:3px solid #90e0ef;border-radius:50%;padding:10px;}

        /* UTILS */
        .opahidden{opacity:0 !important; transform:scale(0) !important; transition:all 0.7s ease;}
        #linkmp3 {display: none;}
	    b.biru-muda{color:#90e0ef}
        b.putih{padding:5px;background:rgba(0,119,182,.4);border-radius:18px;border: 1px solid rgba(255,255,255,0.3);}

        /* EFEK KLIK & HATI BERGUGURAN (BIRU) */
        .click-effect {position: fixed; width: 8px; height: 8px; border-radius: 50%; background: rgba(144, 224, 239, 0.6); pointer-events: none; transform: translate(-50%, -50%); animation: click-animation 0.3s ease-out forwards; z-index: 99999;}
        @keyframes click-animation { 0% { transform: translate(-50%, -50%) scale(1); opacity: 1; } 100% { transform: translate(-50%, -50%) scale(2); opacity: 0; } }
        .heart-icon {z-index:100;width: 25px;height: 25px;position: fixed;animation: heartMove linear 1;top: -10vh;}
        @keyframes heartMove { 0% {transform: translateY(-10vh);} 100% {transform: translateY(100vh);} }
        svg.line{fill: none;stroke: #90e0ef;stroke-width: 2;animation: moving .7s linear infinite alternate;}
        @keyframes moving { from {transform: translateY(0);} to {transform: translateY(-5px);} }
        .spin{animation: spin 3s linear infinite alternate;}
        @keyframes spin { from { transform: rotate(20deg); } to { transform: rotate(-20deg); } }
    </style>
</head>
<body>

    <!-- HALAMAN 1: OVERLAY COVER -->
	<div class="overlay" id="halaman1">
		<div class="cover">
	    	       <p>Sentuh untuk Mulai Cintakuu🤍✨</p>
		        <div class="awalan" id="btnMulai">
	            <svg class='line' fill='none' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'><g transform='translate(2.000000, 2.000000)'><path d='M9.27542857,0.714285714 C14.0030476,0.714285714 17.836381,4.54666667 17.836381,9.2752381 C17.836381,14.0038095 14.0030476,17.8361905 9.27542857,17.8361905 C4.54685714,17.8361905 0.71447619,14.0038095 0.71447619,9.2752381 C0.71447619,4.54666667 4.54685714,0.714285714 9.27542857,0.714285714 Z'></path><path d='M17.8989524,16.487619 C18.678,16.487619 19.3094286,17.12 19.3094286,17.8980952 C19.3094286,18.6780952 18.678,19.3095238 17.8989524,19.3095238 C17.1199048,19.3095238 16.4875238,18.6780952 16.4875238,17.8980952 C16.4875238,17.12 17.1199048,16.487619 17.8989524,16.487619 Z'></path></g></svg>
	            <label style="font-size:16px; cursor: pointer; color: #90e0ef;">S.id/dirimulah</label>
	        </div>
	    </div>
    </div>
  
    <!-- BACKGROUND BLUR - DIUBAH MENJADI FOTO YANG DIMINTA -->
	<div id="bodyblur">
	   <img src="IMG-20260601-WA0106.jpg" id="wallpaper"/>
	</div>
	
	<!-- File Lagu Stronger -->
	<audio src="musik.mp3" id="linkmp3" preload="auto"></audio>
	
    <!-- HALAMAN 2: AMPLOP -->
    <div id="halaman2" class="envlope-wrapper">
        <div id="envelope" class="close">
            <div class="wax-seal"></div>
            <div class="front flap"></div>
            <div class="front pocket"></div>
            <div class="letter">
                <div class="message">
                    <p>UNTUK ANEKUU TERCINTA🩵✨</p>
                    <p>......</p>
                </div>
                            </div>
        </div>
        <div class="reset">
           <button id="open">Buka Surat ini Yah!!! 
                           SAYANGKUUU🩵✨</button>
        </div>
    </div>
    
   <!-- HALAMAN 3: KATA-KATA MINTA MAAF -->
 <div class="stiker" id="stikerLirik">
            <img id="main-stiker" src="giphy.gif" />
        </div>

    <div id="halaman3" class="halaman-maaf">
        <div class="box-maaf">
             <p id="teksMaaf"></p>
            <button class="btn-next" id="btnHalamanTerakhir"      
         style="display:none;"">BACA SAMPAI AKHIR YAH!!!
       💕✌🏼</button>
        </div>
    </div>
    <!-- HALAMAN 4: HALAMAN TERAKHIR SINKRONISASI FOTO & TEKS -->
    <div id="halaman4" class="halaman-galeri">
        <div class="stiker" id="stikerLirik">
            <img id="main-stiker" src="MANISO.gif."" />
        </div>

        <div class="photo-container">
            <img class="slide-photo" src="IMG_20260616_041113.jpg" id="p1">
            <img class="slide-photo" src="IMG-20260306-WA0090.jpg" id="p2">
            <img class="slide-photo" src="IMG-20260131-WA0058.jpg" id="p3">
            <img class="slide-photo" src="IMG-20250630-WA0003.jpg" id="p4">
            <img class="slide-photo" src="IMG-20260616-WA0012.jpg" id="p5">
            <img class="slide-photo" src="IMG-20260131-WA0058.jpg" id="p6">
            <img class="slide-photo" src="IMG_20260616_041144.jpg" id="p7">

      </div>

        <div class="lirik-container">
            <p class="lirik-text" id="lirikTeks"></p>
            <p class="terjemahan-text" id="terjemahanTeks"></p>
        </div>
    </div>

<script>
    // Efek Klik Lingkaran Global
    document.addEventListener("click", function (e) {
        const circle = document.createElement("div");
        circle.classList.add("click-effect");
        circle.style.left = `${e.pageX}px`;
        circle.style.top = `${e.pageY}px`;
        document.body.appendChild(circle);
        circle.addEventListener("animationend", () => circle.remove());
    });

    const audio = document.getElementById('linkmp3');
    const halaman1 = document.getElementById('halaman1');
    const halaman2 = document.getElementById('halaman2');
    const halaman3 = document.getElementById('halaman3');
    const halaman4 = document.getElementById('halaman4');
    const envelope = document.getElementById('envelope');
    const btnMulai = document.getElementById('btnMulai');
    const btnOpen = document.getElementById('open');
    const btnNext = document.getElementById('btnHalamanTerakhir');
    const stikerLirik = document.getElementById('stikerLirik');
    const wallpaper = document.getElementById('wallpaper');
    const lirikTeks = document.getElementById('lirikTeks');
    const terjemahanTeks = document.getElementById('terjemahanTeks');

    // TRANSISI HALAMAN 1 -> HALAMAN 2
    btnMulai.onclick = function() {
        halaman1.classList.add('opahidden');
        setTimeout(() => {
            halaman1.style.display = "none";
            halaman2.style.display = "flex";
        }, 600);
    }

    // TRANSISI HALAMAN 2 -> HALAMAN 3
    envelope.addEventListener('click', bukaSurat);
    btnOpen.addEventListener('click', bukaSurat);

    let suratSudahDibuka = false;
    function bukaSurat() {
        if (suratSudahDibuka) return;
        suratSudahDibuka = true;
        
        envelope.classList.remove("close");
        envelope.classList.add("open");
        
        const rect = envelope.getBoundingClientRect();
        const centerX = rect.left + (rect.width / 2);
        const centerY = rect.top + (rect.height / 2);
        buatLedakanPetasan(centerX, centerY);
        
        setTimeout(() => {
            halaman2.classList.add('opahidden');
            setTimeout(() => {
                halaman2.style.display = "none";
                halaman3.style.display = "flex";
                
                let ditandaiSelesai = false;
                const pemicuTombol = () => {
                    if (!ditandaiSelesai) {
                        ditandaiSelesai = true;
                        const cursor = document.querySelector("#teksMaaf .ti-cursor");
                        if(cursor) cursor.style.display = "none";
                        btnNext.style.display = "inline-block";
                    }
                };

                new TypeIt("#teksMaaf", {
                    strings: 
"Anee Dev Mintaa Maaf eee..Klo selama ini Dev main buat Anee pung hati saki jalan      truss....mulai dari Dev Punya Ucapan, Tuturkata,Dan Dev pung sikap yang membuat Anee emosi,sedih,sampai menangis,Tagal Dev punya sikap dan Ane Dev dsini cuma mau blg maaff bnyakk banyakk eee..Sayangg,Dan juga Dev mau blg makasii banyakk sekalii Anee selalu ada for Dev,mau temani Dev diSaat susah maupun senang makasihhh banyakk seklii mau mengerti, mendengar, dan memahami segala tentang Dev,Disini Dev Harap Kiranya Dev Pung Nona Kecil 1 ni Yang Dev SAYANG Dann Dev CINTAII.. Bisa Maafkann Dev Dengan SEPENUH HATIIIIIII...🥺🙏 ILoveYouuSooMuchhhhh...💋💋💋",
                    speed: 100,
                    cursor: true,
                    afterComplete: pemicuTombol
                }).go();

                setTimeout(pemicuTombol, 7000);
            }, 600);
        }, 1500);
    }

    function buatLedakanPetasan(x, y) {
        const jumlahPartikel = 120; 
        const emojisCinta = ["🩵", "💋", "🧚🏼‍♀️", "💌", "🪼", "❤", "✨","🪽","⭐","❤️‍🔥"];

        for (let i = 0; i < jumlahPartikel; i++) {
            let partikel;
            const tipeAcak = Math.random();

            if (tipeAcak < 0.3) {
                partikel = document.createElement("img");
                partikel.src = "depositphotos_518411404-stock-photo-black-background-white-inscription-love.jpg";
                partikel.classList.add("firework-particle", "text-iloveyou");
            } else if (tipeAcak < 0.6) {
                partikel = document.createElement("img");
                partikel.src = "png-transparent-heart-emoji-color-blue-heart-love-blue-heart-thumbnail.png";
                partikel.classList.add("firework-particle");
            } else {
                partikel = document.createElement("div");
                partikel.innerText = emojisCinta[Math.floor(Math.random() * emojisCinta.length)];
                partikel.classList.add("firework-particle", "emoji");
            }

            partikel.style.left = `${x}px`;
            partikel.style.top = `${y}px`;

            const sudut = Math.random() * Math.PI * 2;
            const jarakSembur = 90 + Math.random() * 200; 
            const targetX = `${Math.cos(sudut) * jarakSembur}px`;
            const targetY = `${Math.sin(sudut) * jarakSembur}px`;
            const rotasiAcak = `${Math.random() * 360 - 180}deg`;

            partikel.style.setProperty('--x', targetX);
            partikel.style.setProperty('--y', targetY);
            partikel.style.setProperty('--r', rotasiAcak);

            partikel.style.animationDelay = `${Math.random() * 0.1}s`;
            partikel.style.animationDuration = `${0.6 + Math.random() * 0.6}s`;

            document.body.appendChild(partikel);

            partikel.addEventListener("animationend", () => {
                partikel.remove();
            });
        }
    }

       // TRANSISI HALAMAN 3 -> HALAMAN TERAKHIR
    btnNext.onclick = function() {
        audio.load();
        audio.play().catch(e => console.log("Audio ditahan browser:", e));

        halaman3.classList.add('opahidden');
        setTimeout(() => {
            halaman3.style.display = "none";
            halaman4.style.display = "flex"; 
            stikerLirik.style.display = "flex";
            wallpaper.style.transform = "scale(1.2)";

            // Waktu lirik disesuaikan dengan lagu Anda:
            setTimeout(() => { 
                gantiSlide("p1", "I'm sorry, if I say, I need you,", "Maafkan aku jika aku bilang, \"Aku membutuhkanmu\"", 60); 
            }, 500);

            setTimeout(() => { 
                gantiSlide("p2", "But I don't care I'm not scared of love", "Tapi aku tidak peduli Aku tidak takut cinta", 60); 
            }, 4500);

            setTimeout(() => { 
                gantiSlide("p3", "Cause when I'm not with you I'm weaker", "Karena saat aku tidak bersamamu aku lebih lemah", 60); 
            }, 8700);

            setTimeout(() => { 
                gantiSlide("p4", "Is that so wrong? Is it so wrong", "A7a itu salah? Apa ini salah", 60); 
            }, 12700);

            setTimeout(() => { 
                gantiSlide("p5", "That you make me strong", "Kalau kamu membuatku kuat", 60); 
            }, 15000);

        }, 600);
    }
    function gantiSlide(idFoto, teksLirik, teksTerjemahan, spd, gifStiker = "") {
        // Hapus kelas aktif dari seluruh foto agar menghilang dan mereset ukuran scale
        document.querySelectorAll('.slide-photo').forEach(img => {
            img.classList.remove('active');
            img.style.transform = "scale(1)"; // Reset ukuran dasar saat tersembunyi
        });
        
        // Aktifkan satu foto tertentu secara 1 per 1
        const fotoAktif = document.getElementById(idFoto);
        if(fotoAktif) {
            // Memicu rendering transisi dan efek Zoom-In perlahan
            setTimeout(() => {
                fotoAktif.classList.add('active');
            }, 50);
        }
        
        if(gifStiker !== "") {
            document.getElementById('main-stiker').src = gifStiker;
        }

        // Tampilkan lirik utama dengan TypeIt
        lirikTeks.innerHTML = "";
        new TypeIt("#lirikTeks", {
            strings: teksLirik,
            speed: spd,
            cursor: false
        }).go();

        // Tampilkan terjemahan bahasa indonesia tepat di bawahnya secara instan / cepat
        terjemahanTeks.innerHTML = "";
        new TypeIt("#terjemahanTeks", {
            strings: teksTerjemahan,
            speed: 20,
            cursor: false
        }).go();
    }
    
    function berjatuhan() {
        const heart = document.createElement("div");
        heart.innerHTML = "<svg class='line spin' style='opacity:.7;z-index:100;fill:#00b4d8;' xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'><g transform='translate(2.550170, 3.550158)'><path d='M0.371729633,8.89614246 C-0.701270367,5.54614246 0.553729633,1.38114246 4.07072963,0.249142462 C5.92072963,-0.347857538 8.20372963,0.150142462 9.50072963,1.93914246 C10.7237296,0.0841424625 13.0727296,-0.343857538 14.9207296,0.249142462 C18.4367296,1.38114246 19.6987296,5.54614246 18.6267296,8.89614246 C16.9567296,14.2061425 11.1297296,16.9721425 9.50072963,16.9721425 C7.87272963,16.9721425 2.09772963,14.2681425 0.371729633,8.89614246 Z'></path><path d='M13.23843,4.013842 C14.44543,4.137842 15.20043,5.094842 15.15543,6.435842'></path></g></svg>";
        heart.className = "heart-icon";
        heart.style.left = (Math.random() * 93) + "vw";
        heart.style.animationDuration = (Math.random() * 2) + 2.5 + "s";
        document.body.appendChild(heart);
    }

    setInterval(function () {
        const heartArr = document.querySelectorAll(".heart-icon");
        if (heartArr.length > 60) { heartArr[0].remove(); }
    }, 100);
</script>

</body>
</html>

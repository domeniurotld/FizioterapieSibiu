<template>
    <div>
        <div class="card bg-dark text-white" style="border-radius: 0; border: none;">
            <img class="card-img main-section-img" src="/assets/images/waiting-room.jpg" alt="Card image">
            <div class="dark-overlay"></div>
            <div class="card-img-overlay card-img-text">
                <div class="moto-container">
                    <div class="moto-title-size">
                        <h4 class="card-title main-moto">Aparatură</h4>
                    </div>
                    <div class="moto-description-size">
                        <p class="card-text moto-description">Aparatură de ultima generație, nou adusa pe piața! </p>
                    </div>
                    <div class="row sections-buttons">
                        <div class="contact-button">
                            <button class="top-section-button" @click="scrollToSection('crioterapie')"> 
                                <span>Crioterapie</span>
                            </button>
                        </div>
                        <div class="contact-button">
                            <button class="top-section-button" @click="scrollToSection('electroterapie')"> 
                                <span>Electroterapie</span>
                            </button>
                        </div>
                        <div class="contact-button">
                            <button class="top-section-button" @click="scrollToSection('diatermie')"> 
                                <span>Diatermie</span>
                            </button>
                        </div>
                        <div class="contact-button">
                            <button class="top-section-button" @click="scrollToSection('laseroterapie')"> 
                                <span>Laseroterapie</span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="crioterapie" class="section-content">
            <div class="text-content">
                <h1 class="page-title">Crioterapie</h1>
                <hr>
                <p class="simple-text">
                    Aparatul de crioterapie este o tehnologie inovatoare care utilizează temperaturi extreme scăzute pentru a oferi beneficii terapeutice și de recuperare. Crioterapia este o formă de terapie care implică expunerea controlată a corpului la temperaturi foarte scăzute, de obicei sub -100 grade Celsius, timp de scurtă durată.
                </p>
                <p class="simple-text">
                    Acest aparat avansat oferă o modalitate eficientă de tratare a inflamațiilor, reducerea durerii, îmbunătățirea circulației sângelui și accelerarea procesului de vindecare. Pacienții care folosesc crioterapia raportează adesea o senzație de energie, revigorare și relaxare după procedură.
                </p>
                <p class="simple-text">
                    Prin intermediul unei camere speciale sau a unui dispozitiv controlat de un terapeut specializat, pacienții sunt expuși la aceste temperaturi scăzute pentru o perioadă scurtă de timp, de obicei câteva minute. Această expoziție controlată la frig ajută la reducerea inflamațiilor, stimularea sistemului imunitar și creșterea nivelului de endorfine, hormonii responsabili de senzația de bine.
                </p>
                <p class="simple-text">
                    Folosit în diverse domenii precum medicina sportivă, recuperare post-chirurgicală sau tratamentul durerilor cronice, aparatul de crioterapie este o resursă valoroasă pentru cei care își doresc să-și îmbunătățească sănătatea și performanța fizică.
                </p>
            </div>
        </div>
        <div id="electroterapie" class="section-content">
            <div class="text-content">
                <h1 class="page-title">Electroterapie</h1>
                <hr>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Electrostimulator muscular (EMS):</b> Acest tip de aparat trimite impulsuri electrice către mușchi, determinându-i să se contracte și să se relaxeze. Este adesea utilizat în recuperare musculară după leziuni sau în scopuri de antrenament.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Electrostimulator nervos transcutanat (TENS):</b> Acesta folosește impulsuri electrice pentru a bloca semnalele de durere către creier, oferind astfel un efect analgezic. Este frecvent utilizat pentru a trata durerile cronice, cum ar fi cele de spate sau de articulații.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Electroterapie cu ultrasunete:</b> Acest tip de electroterapie utilizează ultrasunetele pentru a penetra țesuturile profunde, ajutând la ameliorarea durerii și la îmbunătățirea circulației sângelui. Este adesea utilizat în tratamentul leziunilor musculare și ale țesuturilor moi.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Electroterapie cu laser (LELT):</b> Acest tip de electroterapie utilizează radiații laser pentru a stimula procesele de vindecare în țesuturile afectate. Este eficient în tratarea durerilor cronice și a leziunilor tisulare.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Electroterapie cu impulsuri de frecvență înaltă (HVPC):</b> Acest tip de electroterapie folosește impulsuri de curent continuu de înaltă frecvență pentru a îmbunătăți circulația sângelui și a promova vindecarea țesuturilor.
                </p>
                <p class="simple-text">
                    Indiferent de tipul de aparat de electroterapie utilizat, aceste dispozitive sunt adesea utilizate în cadrul tratamentelor de fizioterapie și sunt concepute pentru a fi sigure și eficiente sub supravegherea unui profesionist medical. Utilizarea lor corectă poate fi benefică în gestionarea durerii și în accelerarea procesului de recuperare în urma unei varietăți de afecțiuni și leziuni.
                </p>
            </div>
        </div>
        <div id="diatermie" class="section-content">
            <div class="text-content">
                <h1 class="page-title">Diatermie</h1>
                <hr>
                <p class="simple-text">
                    Funcționarea unui aparat pentru diatermie se bazează pe conversia energiei electromagnetice în căldură în țesuturile corpului. Undele electromagnetice pătrund în corp și sunt absorbite de țesuturile care prezintă o rezistență electrică mai mare, cum ar fi mușchii, tendoanele și ligamentele. Aceasta determină creșterea temperaturii locale în aceste zone, ceea ce poate avea mai multe efecte terapeutice, cum ar fi:
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Relaxarea musculară:</b> Căldura produsă de diatermie poate ajuta la relaxarea mușchilor tensionați sau încordați.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Creșterea circulației sângelui:</b> Diatermia poate stimula fluxul sanguin către zonele tratate, ceea ce poate îmbunătăți alimentarea cu nutrienți și oxigen a țesuturilor și poate accelera procesul de vindecare.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Reducerea durerii:</b> Efectul de încălzire al diatermiei poate ajuta la ameliorarea durerii asociate cu diverse afecțiuni, cum ar fi artrita sau leziunile musculare.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Redresarea colagenului:</b> Diatermia poate ajuta la îmbunătățirea elasticității și a flexibilității țesuturilor, prin promovarea producerii de colagen.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Reducerea inflamației:</b> Căldura generată de diatermie poate ajuta la reducerea inflamației în țesuturi, ceea ce poate fi util în gestionarea afecțiunilor inflamatorii.
                </p>
                <p class="simple-text">
                    Aparatele pentru diatermie pot avea diferite modalități de aplicare a undelor electromagnetice, inclusiv terapie capacitivă și terapie inductivă. Ele sunt utilizate adesea în cadrul tratamentelor de fizioterapie și sunt supravegheate de către profesioniști medicali calificați pentru a asigura o utilizare sigură și eficientă.
                </p>
            </div>
        </div>
        <div id="laseroterapie" class="section-content" style="padding-bottom: 2.5rem;">
            <div class="text-content">
                <h1 class="page-title">Ultrasunete si Laseroterapie</h1>
                <hr>
                <p class="simple-text">
                    Un aparat de ultrasunete și laseroterapie este un dispozitiv medical care combină două tehnologii terapeutice diferite pentru a trata diverse afecțiuni și pentru a promova vindecarea. Acest tip de aparat este utilizat adesea în domeniul fizioterapiei și al medicinii sportive pentru a trata leziunile musculare, articulare și țesuturile moi.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Ultrasunete:</b> Această parte a aparatului folosește unde sonore de înaltă frecvență pentru a penetra în profunzime în țesuturile corpului. Ultrasunetele pot pătrunde mai adânc decât alte tehnologii de terapie, ajungând până la 5 cm în țesuturi. Când ultrasunetele sunt aplicate pe piele cu ajutorul unei sonde, acestea produc vibrații care generează căldură în țesuturile tratate. Acest efect termic poate îmbunătăți circulația sângelui, poate reduce durerea și inflamația, și poate accelera procesul de vindecare prin stimularea metabolismului celular și a regenerării țesuturilor.
                </p>
                <p class="simple-text" style="margin-left: 1rem;">
                    <b>• Laseroterapie (terapie cu laser de joasă intensitate):</b> Această parte a aparatului folosește radiații laser cu intensitate scăzută pentru a influența țesuturile corpului. Laserul emite lumină coerentă, care poate pătrunde în țesuturile superficiale și profunde. Efectele terapeutice ale laserului includ reducerea durerii, accelerarea vindecării rănilor, reducerea inflamației, stimularea regenerării celulare și a creșterii țesutului sănătos. De asemenea, laserul poate ajuta la creșterea fluxului sanguin în zonele tratate și poate îmbunătăți funcția sistemului limfatic.
                </p>
                <p class="simple-text">
                    Combinația de ultrasunete și laseroterapie într-un singur aparat oferă avantajele ambelor tehnologii terapeutice, permițând utilizatorilor să beneficieze de o gamă mai largă de tratamente și să abordeze diferite afecțiuni și leziuni în mod eficient. Aparatele de ultrasunete și laseroterapie sunt utilizate cu precădere în centrele de fizioterapie, cabinetele medicale și în mediile sportive pentru tratarea leziunilor, recuperarea după traumatisme și îmbunătățirea performanței fizice.
                </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  methods: {
    scrollToSection(sectionId) {
      const section = document.getElementById(sectionId);
      if (section) {
        section.scrollIntoView({ behavior: 'smooth' });
      }
    }
  }
}
</script>

<style scoped>
    .mobile-only {
        display: none;
    }
    .main-section-img {
        height: 600px; 
        object-fit: cover;
    }
    .second-section-img {
        height: 600px; 
        object-fit: cover;
    }
    .dark-overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%; /* Full width to cover the image */
        height: 100%;
        background: radial-gradient(#fffafa73, #fffafa73); /* Gradient from dark to transparent */
        pointer-events: none; /* Prevents interaction with the overlay */
    }
    .main-moto {
        font-size: 3rem;
        font-weight: 700;
        text-transform: uppercase;
        justify-content: center;
        display: flex;
    }
    .moto-description {
        font-size: 1.7rem;
        font-weight: 600;
        justify-content: center;
        display: flex;
        color: #162049;
        text-align: center;
    }
    .top-section-button {
        font-size: 1.5rem;
        color: white;
        background: #252f5b;
        border: none;
        padding: 0.4rem 1.2rem;
        display: inline-flex;
        align-items: center;
        justify-content: center;
    }
    .card-button-size {
        width: 100%; 
        display: flex; 
        justify-content: center;
    }
    .card-button {
        font-size: 1.5rem;
        color: black;
        background: transparent;
        border-width: 2px;
        border-color: black;
        border-radius: 10px;
        padding: 0.4rem 1.2rem;
        margin-right: 1rem;
    }
    .card-button:hover {
        color: white;
        background: black;
    }
    .card-img-text {
        padding: 3rem 5rem;
        display: flex;
        align-items: center;
    }
    .main-section {
        padding: 1rem 5rem;
    }
    .main-section-title {
        width: 100%;
        font-size: 2rem;
        font-weight: 700;
        margin-bottom: 0.5rem;
    }

    .simple-text {
        font-size: 1.2rem;
        color: #162049;
        margin-top: 0;
    }

    .small-description {
        font-size: 1.4rem;
    }

    .page-title {
        
    }

    .image-container {
        flex: 1;
        max-width: 500px;
        height: auto;
        overflow: hidden;
        border-radius: 5px;
    }

    .image-container img {
        max-height: 300px;
    }

    .section-content {
        display: flex;
        flex-wrap: wrap;
        gap: 2rem;
        padding: 2.5rem 5rem;
        padding-bottom: 0;
    }

    .text-content {
        flex: 1;
    }
    
    .feature-card {
        width: 30%;
        border-width: 3px;
        border-radius: 15px;
        border-color: #656262;
        padding: 2rem;
    }

    .contact-button {
        width: auto; 
        display: flex;
        justify-content: center;
    }

    .moto-container {
        display: flex; 
        width: 100%;
        flex-direction: column;
    }

    .moto-card {
        width: 50%;
    }

    .moto-title-size {
        width: 100%; 
        margin-top: 1rem;
        color: #162049;
    }

    .moto-description-size {
        width: 100%; 
        margin-top: 1rem;
    }
    hr {
        margin: 0;
        margin-bottom: 1.2rem;
        border: 1px solid #252f5b;
    }
    h1 {
        color: #162049;
    }
    #aparatura {
        background-color: #162049;
    }
    #aparatura .page-title {
        margin-bottom: 1rem;
        color: white;
    }
    #aparatura .simple-text {
        color: white;
    }
    #aparatura .top-section-button {
        border: 1px solid white;
        background: transparent;
    }
    #aparatura .top-section-button:hover {
        border: 1px solid white;
        background: white;
        color: #162049;
    }

    .sections-buttons {
        width: 100%; 
        justify-content: center; 
        margin-top: 2rem;
    }

    @media (max-width: 768px) {
    .section-content {
      padding: 1rem 2rem;
      flex-direction: column;
        gap: 1rem;
    }
    .image-container {
      max-width: 100%;
      max-height: 300px;
    }
    .image-container img {
        max-height: 300px;
    }
    .simple-text {
      font-size: 1rem;
    }
    .moto-container {
        flex-direction: column;
        gap: 1rem;
        align-items: center;
    }
    .moto-card {
        width: 100%;
    }
    .moto-title-size {
        width: 100%;
    }
    .main-moto {
        font-size: 2rem;
    }
    .moto-description-size {
        width: 100%;
    }
    .moto-description, .small-description {
        font-size: 1rem;
    }

    .main-section-img {
        height: 450px;
    }
    .second-section-img {
        height: 800px; 
    }
    .feature-card {
        width: 100%;
        padding: 1rem;
    }
    .card-button {
        font-size: 1.2rem;
    }
    .top-section-button {
        font-size: 1.2rem;
        width: 150px;
    }
    .contact-button {
        margin-top: 1rem;
        justify-content: center;
        display: flex;
    }
    .main-section {
        padding: 1rem 1rem !important;
    }
    .card-img-text {
        padding: 1rem 1rem !important;
    }
    hr {
      margin: 0;
      margin-bottom: 1rem;
    }
    .sections-buttons {
        margin-top: 0;
    }
}
</style>
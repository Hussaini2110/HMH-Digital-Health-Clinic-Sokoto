<!DOCTYPE html>
<html lang="ha">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HMH Digital Health Clinic</title>
<style>
    body { font-family: Arial, sans-serif; margin:0; padding:0; background:#f4f7f9; color:#333; }
    header { background:#4CAF50; color:white; padding:20px; text-align:center; }
    nav { display:flex; justify-content:center; background:#2e7d32; }
    nav a { color:white; padding:14px 20px; text-decoration:none; }
    nav a:hover { background:#81c784; color:#000; }
    section { padding:40px 20px; }
    h2 { color:#2e7d32; }
    .services { display:flex; flex-wrap:wrap; gap:20px; justify-content:center; }
    .service { background:white; padding:20px; flex:1 1 250px; box-shadow:0 0 10px rgba(0,0,0,0.1); border-radius:10px; }
    .booking, .contact { background:white; padding:20px; box-shadow:0 0 10px rgba(0,0,0,0.1); border-radius:10px; max-width:600px; margin:auto; }
    input, textarea, select, button { width:100%; padding:10px; margin:5px 0; border-radius:5px; border:1px solid #ccc; }
    button { background:#4CAF50; color:white; border:none; cursor:pointer; }
    button:hover { background:#45a049; }
    .gallery { display:flex; flex-wrap:wrap; gap:10px; justify-content:center; }
    .gallery img { width:200px; height:150px; object-fit:cover; border-radius:5px; }
    footer { background:#2e7d32; color:white; text-align:center; padding:10px; }
    .lang-toggle { position:absolute; top:20px; right:20px; cursor:pointer; color:white; background:#388E3C; padding:5px 10px; border-radius:5px; }
</style>
</head>
<body>

<header>
    <h1>HMH Digital Health Clinic</h1>
    <p>Lafiya da Kulawa daga Allah</p>
    <div class="lang-toggle" onclick="toggleLang()">Switch Language / Sauya Harshe</div>
</header>

<nav>
    <a href="#home">Home / Gida</a>
    <a href="#services">Services / Ayyuka</a>
    <a href="#booking">Booking / Ajiyar Lokaci</a>
    <a href="#gallery">Gallery / Hotuna</a>
    <a href="#contact">Contact / Tuntuɓi</a>
</nav>

<section id="home">
    <h2>Welcome / Barka da zuwa!</h2>
    <p>HMH Digital Health Clinic yana bada cikakken kulawa da lafiya, daga diagnostics zuwa treatments, da health education.</p>
</section>

<section id="services">
    <h2>Our Services / Ayyukanmu</h2>
    <div class="services">
        <div class="service"><h3>Diagnostic & Medical Checkup</h3><p>Full health assessment for patients.</p></div>
        <div class="service"><h3>Treatments / Magani</h3><p>Professional treatments for various health conditions.</p></div>
        <div class="service"><h3>Investigations / Bincike</h3><p>Lab and medical investigations for accurate diagnosis.</p></div>
        <div class="service"><h3>Health Education / Ilimin Lafiya</h3><p>Education programs to promote wellness and prevention.</p></div>
        <div class="service"><h3>Diseases Surveillance / Kula da Cutarwa</h3><p>Monitoring and controlling disease outbreaks.</p></div>
    </div>
</section>

<section id="booking">
    <h2>Book Appointment / Yi Ajiyar Lokaci</h2>
    <div class="booking">
        <form id="bookingForm">
            <input type="text" placeholder="Full Name / Sunanka" required>
            <input type="email" placeholder="Email" required>
            <input type="tel" placeholder="Phone / Lambar Waya" required>
            <select required>
                <option value="">Select Service / Zaɓi Aiki</option>
                <option>Diagnostic & Medical Checkup</option>
                <option>Treatments</option>
                <option>Investigations</option>
                <option>Health Education</option>
                <option>Diseases Surveillance</option>
            </select>
            <input type="date" required>
            <button type="submit">Submit / Aika</button>
        </form>
    </div>
</section>

<section id="gallery">
    <h2>Gallery / Hotuna</h2>
    <div class="gallery">
        <img src="https://via.placeholder.com/200x150" alt="Clinic">
        <img src="https://via.placeholder.com/200x150" alt="Medical Staff">
        <img src="https://via.placeholder.com/200x150" alt="Patient Care">
        <img src="https://via.placeholder.com/200x150" alt="Lab">
    </div>
</section>

<section id="contact">
    <h2>Contact Us / Tuntuɓi Mu</h2>
    <div class="contact">
        <form>
            <input type="text" placeholder="Full Name / Sunanka" required>
            <input type="email" placeholder="Email" required>
            <textarea placeholder="Message / Sako" required></textarea>
            <button type="submit">Send / Aika</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2025 HMH Digital Health Clinic. Duk Haƙƙin Mallaka.</p>
</footer>

<script>
function toggleLang(){
    alert("Language toggle feature placeholder! (Hausa / English)");
}
document.getElementById('bookingForm').addEventListener('submit', function(e){
    e.preventDefault();
    alert('Booking submitted! Feature placeholder for backend integration.');
});
</script>

</body>
</html>

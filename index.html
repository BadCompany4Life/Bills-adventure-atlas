<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<title>Bill's Adventure Atlas</title>

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link
rel="stylesheet"
href="https://unpkg.com/leaflet/dist/leaflet.css"
/>

<style>
body {
margin: 0;
font-family: Arial;
background: #0f172a;
color: white;
}

#map {
height: 60vh;
}

#panel {
padding: 12px;
}

.card {
background: #1e293b;
padding: 12px;
border-radius: 12px;
margin-top: 10px;
}

button {
width: 100%;
padding: 12px;
margin-top: 10px;
border: none;
border-radius: 10px;
background: #22c55e;
color: white;
font-weight: bold;
}
</style>

</head>

<body>

<div id="map"></div>
<div id="panel">
<h2>🌲 Bill's Adventure Atlas</h2>
<p>Tap a trail pin to begin</p>
</div>

<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>

<script>
// -----------------------------
// SIMPLE TRAIL DATA (WORKING)
// -----------------------------
const trails = [
{
id: "blackstar",
name: "Black Star Canyon",
lat: 33.8706,
lng: -117.7275,
distance: 7.5,
difficulty: "moderate",
info: "Canyon hike with creek and waterfall area"
},
{
id: "holyjim",
name: "Holy Jim Falls",
lat: 33.6111,
lng: -117.4862,
distance: 5.5,
difficulty: "moderate",
info: "Shaded canyon hike with waterfall"
},
{
id: "whiting",
name: "Whiting Ranch",
lat: 33.6706,
lng: -117.6358,
distance: 8.0,
difficulty: "easy",
info: "Fire road loops and oak forest"
}
];

// -----------------------------
// INIT MAP
// -----------------------------
const map = L.map('map').setView([33.7, -117.75], 10);

L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
maxZoom: 18
}).addTo(map);

// -----------------------------
// ADD MARKERS
// -----------------------------
trails.forEach(t => {

const marker = L.marker([t.lat, t.lng]).addTo(map);

marker.on("click", () => {

document.getElementById("panel").innerHTML = `

<div class="card">

<h2>🥾 ${t.name}</h2>

<p>📏 ${t.distance} miles</p>
<p>⛰ Difficulty: ${t.difficulty}</p>
<p>${t.info}</p>

<button onclick="startHike('${t.name}')">
Start Hike
</button>

</div>

`;

});

});

// -----------------------------
// HIKE MODE (SIMPLE)
// -----------------------------
function startHike(name) {

document.getElementById("panel").innerHTML = `

<div class="card">

<h2>🥾 Hiking: ${name}</h2>

<p>Step 1: Follow trail entrance</p>
<p>Step 2: Stay on main path</p>
<p>Step 3: Continue to destination</p>

<button onclick="location.reload()">
Exit Hike
</button>

</div>

`;

}
</script>

</body>
</html>

# Quieres.html
# Quieres-ser-mi-Novia-
<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>♥ qUIERES sER mI nOVIa ♥</title>
  <style>
    .body {
      background-color: crimson;
      text-align: center;
    }

    .body__title {
      color: white;
    }

    .body__img {
      width: 100%;
      max-width: 512px;
      border-radius: 50%;
    }
  </style>
</head>

<body class="body">
  <h1 class="body__title">♥ Quieres Ser mi Novia ♥</h1>
  <img src="https://frikimaestro.com/wp-content/uploads/2019/10/0005-3.jpg" alt="Foto D My" class="body__img" />
  <br>
  <button id="yes">🌚Si🌚</button>
  <button id="no">😭No😭</button>

  <script>
    const vuttonSi = document.getElementById('yes');
    const vuttonNo = document.getElementById('no');

    const zomosNobios = () => {
      alert('💞Haora somos novios beivi💞');
      alert('😱Soy gay😱');
      location.href = 'https://youtu.be/am1_JLFDFMw?t=19';
    };

    const ebitarKCRompaMyBobo = () => {
      vuttonNo.style.position = 'absolute';
      vuttonNo.style.top = (Math.random() * window.innerHeight + 'px');
      vuttonNo.style.left = (Math.random() * window.innerWidth + 'px');
    };

    vuttonSi.addEventListener('click', zomosNobios);
    vuttonNo.addEventListener('mouseover', ebitarKCRompaMyBobo);
  </script>
</body>

</html>

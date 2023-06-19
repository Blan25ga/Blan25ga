
<h1> Hello, I'm Gabriel! <img src="https://github.com/ABSphreak/ABSphreak/blob/master/gifs/Hi.gif" width="30px"></h1>
<img src="https://media.giphy.com/media/sk6yL9EGVeAcE/giphy.gif" width= 100% />

<table width="100%"  border="0" cellpadding="0" cellspacing="0">

<h2>A little more about me:</h2>

- 🔭 I am currently working as a FreeLancer.
- 🌱 I am currently perfecting myself in the BackEnd area.
- 👯 I am looking to collaborate on any project that increases my knowledge.
- 🤔 I am looking for help in finding a permanent job.
- 💬 Ask me about anything, the idea is to help as much as possible!!!!
- 📫 How to contact me, click 👉 <a href="mailto:gabriel.bl@hotmail.com.ar"> Gabriel Blanco </a>
- ⚡ Fun fact: I love looking for new knowledge alternatives.

  
<div id="contador-visitas"></div>

function obtenerContadorVisitas(usuario) {
  const url = `https://img.shields.io/github/followers/${usuario}?label=Visitas&style=social`;
  
  fetch(url)
    .then(response => response.text())
    .then(data => {
      const contadorVisitas = data.match(/>([^<]+)</)[1];
      document.getElementById("contador-visitas").textContent = contadorVisitas;
    })
    .catch(error => {
      console.error("No se pudo obtener el contador de visitas:", error);
    });
}

const usuario = "Blan25ga";
obtenerContadorVisitas(usuario);

 <tr>
    <td alinear="centro">
      <img align="left" src="https://github-readme-stats.vercel.app/api?username=Blan25ga&show_icons=true&theme=dracula" />
    </td>
    <td alinear="centro">
        <img src="https://github.com/Blan25ga/Blan25ga/blue/master/globe.gif?raw=true" />
    </td>
 </tr>
 
 </table>

## 𝗩𝗶𝘀𝗶𝘁𝗼𝗿𝘀

![visitors](https://visitor-badge.glitch.me/badge?page_id=Blan25ga.Blan25ga)
</br>
⭐️ De [ Blan25ga ](https://github.com/Blan25ga)

file:///C:/Users/Lenovo/AppData/Local/Temp/21055d0b-a28f-46e5-b5ed-17893fc6dbb5_Proje%20Do%C4%9Fu%C5%9F.zip.bb5/Proje%20Do%C4%9Fu%C5%9F/index.html/index.html

document.addEventListener('DOMContentLoaded', function() {
  const images = document.querySelectorAll('.image-gallery img');
  images.forEach(image => {
    image.addEventListener('click', function() {
      alert('Fotoğrafı büyütmek için ilgili alanı tıklayın.');
    });
  });
});

/* Genel stil ayarları */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
  }
  
  /* Header kısmı */
  header {
    background-color: #3498db;
    color: white;
    padding: 20px 0;
  }
  
  header h1 {
    font-size: 36px;
    margin-bottom: 10px;
  }
  
  header p {
    font-size: 18px;
  }
  
  /* Container için merkezi hizalama */
  .container {
    width: 80%;
    margin: 0 auto;
  }
  
  /* Biyografi kısmı */
  .bio {
    background-color: white;
    padding: 40px 0;
    text-align: center;
  }
  
  .bio h2 {
    font-size: 28px;
    margin-bottom: 20px;
  }
  
  /* Başarılar kısmı */
  .achievements {
    background-color: #ecf0f1;
    padding: 40px 0;
    text-align: center;
  }
  
  .achievements h2 {
    font-size: 28px;
    margin-bottom: 20px;
  }
  
  .achievements ul {
    list-style-type: none;
  }
  
  .achievements ul li {
    font-size: 20px;
    margin: 10px 0;
  }
  
  /* Galeri kısmı */
  .gallery {
    background-color: white;
    padding: 40px 0;
  }
  
  .gallery h2 {
    font-size: 28px;
    margin-bottom: 20px;
    text-align: center;
  }
  
  .image-gallery {
    display: flex;
    justify-content: space-around;
  }
  
  .image-gallery img {
    width: 30%;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  .image-gallery img:hover {
    transform: scale(1.05);
    transition: transform 0.3s ease;
  }
  
  /* Footer kısmı */
  footer {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 20px 0;
    margin-top: 40px;
  }
  
  footer p {
    font-size: 16px;
  }

  

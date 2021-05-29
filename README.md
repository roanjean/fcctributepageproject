# fcctributepageproject

  <head>
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Newsreader&display=swap" rel="stylesheet">
    <title>Tribute Page</title>
    <style>
      :root{
        --maincolor: darkslategray;
      }
      body {
        font-family:'Newsreader', sans-serif;
        color: var(--maincolor);
        text-align: center;
      }
      a {
        color: steelblue;
      }
      img{
        max-width: 100%;
        height: auto;
        display: block;
        padding: 3px;
}
      .title {
        background-color:powderblue;
        padding: 5px;
        border-radius: 20px;
      }
      .tribute {
        background-color:lavender;
        padding: 8px;
      }
      ul li {
        list-style-type: none;
      }
      
    </style>
  </head>
  <body>
    <div id="main">
    <div class="title">
      <h1 id="title">Types of Tea</h1>
      <p id="description">Get to know various tea varieties for greater appreciation of one of the most consumed beverages in the world</p>
    </div>
    <div id="img-div">
      <img src="https://images.pexels.com/photos/235925/pexels-photo-235925.jpeg?cs=srgb&dl=pexels-pixabay-235925.jpg&fm=jpg" alt="tea plantation" id="image"><br>
      <figcaption id="img-caption">Tea pickers on their way to harvest.</figcaption>
    </div><br>
    <div class="tribute" id="tribute-info">
      <h2>Types of Tea and Popular Varieties</h2>
      <p>
        <ul>
          <li><strong>Black tea</strong> - made from Camellia sinensis tea plant and fully, or almost fully, oxidized. Popular varieties are assam, darjeeling, earl grey, and English breakfast teas.</li><br>
          <li><strong>Green tea</strong> - made from Camellia sinensis tea plant and unoxidized. Popular varieties are matcha and sencha.</li><br>
          <li><strong>Herbal tea</strong> - made from infused dried herbs, fruits, and flowers. Popular varieties are peppermint, chamomile, and yerba mate teas.</li><br>
          <li><strong>White tea</strong> - made from Camellia sinensis tea plant and slightly oxidized. Popular varieties are silver needle and white peony teas.</li><br>
          <li><strong>Oolong tea</strong> - made from Camellia sinensis tea plant and partially oxidized. </li><br>
          <li><strong>Rooibos tea</strong> - made from dried rooibos plant and partially oxidized. Popular varieties are red rooibos and green rooibos.</li><br>
        </ul>
        </p>
      <h3>
        To learn more, read this comprehensive article of the many  <a href="https://www.artfultea.com/tea-wisdom-1/types-of-tea-a-comprehensive-guide" id="tribute-link" alt="types of tea" target="_blank">types of tea</a>.
      </h3>
    </div>
  </body>
</html>

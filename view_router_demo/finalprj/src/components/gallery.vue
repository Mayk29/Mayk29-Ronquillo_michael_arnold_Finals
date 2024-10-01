<template>
    <div class="gallery">
      <div class="container">
        <h1>Naruto Characters</h1>
        <div class="row">
          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card">
              <img
                src="../assets/naruto.jpg"
                class="card-img-top"
                alt="Naruto Uzumaki"
              />
              <div class="card-body">
                <h5 class="card-title name">Naruto Uzumaki</h5>
                <p class="card-text">
                  Naruto Uzumaki is the titular protagonist of the manga Naruto, created by Masashi Kishimoto. He is a ninja from the fictional Hidden Leaf Village. As a boy, Naruto is ridiculed and ostracized on account of the Nine-Tailed Demon Fox—a malevolent creature that attacked Konohagakure—that was sealed away in his body.
                </p>
              </div>
            </div>
          </div>
  
          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card">
              <img
                src="../assets/sasuke.jpg"
                class="card-img-top"
                alt="Sasuke Uchiha"
              />
              <div class="card-body">
                <h5 class="card-title name">Sasuke Uchiha</h5>
                <p class="card-text">
                    Sasuke Uchiha is a fictional character in the Naruto manga and anime franchise created by Masashi Kishimoto. Sasuke belongs to the Uchiha clan, a notorious ninja family, and one of the most powerful, allied with Konohagakure
                </p>
                <br>
              </div>
            </div>
          </div>
  
          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card">
              <img
                src="../assets/sakura.jpg"
                class="card-img-top"
                alt="Sakura Haruno"
              />
              <div class="card-body">
                <h5 class="card-title name">Sakura Haruno</h5>
                <p class="card-text">
                    Sakura Haruno is a fictional character in the Naruto manga and anime series created by Masashi Kishimoto. Sakura is depicted as a kunoichi affiliated with Konohagakure and a part of Team 7, which consists of herself, Naruto Uzumaki, Sasuke Uchiha, and their sensei Kakashi Hatake.
                </p>
              </div>
            </div>
          </div>
  
          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card">
              <img
                src="../assets/itachi.jpg"
                class="card-img-top"
                alt="Itachi Uchiha"
              />
              <div class="card-body">
                <h5 class="card-title name">Itachi Uchiha</h5>
                <p class="card-text">
                    Itachi Uchiha is a character in the Naruto manga and anime series created by Masashi Kishimoto. Itachi is the older brother of Sasuke Uchiha, and is responsible for killing all the members of their clan, sparing only Sasuke.
                </p>
              </div>
            </div>
          </div>
  
          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card">
              <img
                src="../assets/kakashi.jpg"
                class="card-img-top"
                alt="Kakashi Hatake"
              />
              <div class="card-body">
                <h5 class="card-title name">Kakashi Hatake</h5>
                <p class="card-text">
                    Kakashi Hatake is a fictional character and one of the main protagonists in the Naruto manga and anime series created by Masashi Kishimoto. In the story, Kakashi is the teacher of Team 7, consisting of the series' primary characters, Naruto Uzumaki, Sasuke Uchiha, and Sakura Haruno.
                </p>
              </div>
            </div>
          </div>
  
          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card">
              <img
                src="../assets/nagato.jpg"
                class="card-img-top"
                alt="Nagato"
              />
              <div class="card-body">
                <h5 class="card-title name">Nagato</h5>
                <p class="card-text">
                    Nagato, known primarily under the alias of Pain, is a fictional character in the manga and anime series Naruto created by Masashi Kishimoto. Nagato is the figurehead leader of the Akatsuki who wishes to capture the tailed beasts sealed into various people around the shinobi world.
                </p>
              </div>
            </div>
          </div>
  
          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card">
              <img
                src="../assets/hinata.jpg"
                class="card-img-top"
                alt="Hinata Hyuga"
              />
              <div class="card-body">
                <h5 class="card-title name">Hinata Hyuga</h5 >
                <p class="card-text">
                    Hinata Hyuga is a fictional character in the anime and manga Naruto, created by Masashi Kishimoto. Hinata is a kunoichi and the former heiress of the Hyūga clan from the fictional village of Konoha.
                </p>
              </div>
            </div>
          </div>
  
          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card">
              <img
                src="../assets/tenten.jpg"
                class="card-img-top"
                alt="Tenten"
              />
              <div class="card-body">
                <h5 class="card-title name">Tenten</h5>
                <p class="card-text">
                    Tenten is one of the main supporting characters in the Naruto anime/manga series and the Boruto: Naruto Next Generations anime/manga series. Shis a chūnin-level kunoichi of Konohagakure and member of Team Guy.
                </p>
              </div>
            </div>
          </div>
  
          <div class="col-lg-4 col-md-6 mb-4">
            <div class="card">
              <img
                src="../assets/ino.jpg"
                class="card-img-top"
                alt="Ino Yamanaka"
              />
              <div class="card-body">
                <h5 class="card-title name">Ino Yamanaka</h5>
                <p class="card-text">
                    Ino Yamanaka is a headstrong ninja of the Hidden Leaf Village and a member of Team 10 as their medic, Ino is a member of the Yamanaka-Clan of Konoha. She uses a family ninja technique that can control the minds of her enemies. She is married to Sai and had a son with him named Inojin.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'gallery',
    data () {
      return {
        msg: 'Welcome to Gallery Page'
      }
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h1, h2 {
    font-weight: normal;
  }
  h1{
    margin-top: 2em;
    margin-bottom: 2em;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
  .img-about{
    width: 500px;
    margin-top: 4em;
  
  }
  .name {
   font-weight: bold;
   color: orange;
  }
  </style>
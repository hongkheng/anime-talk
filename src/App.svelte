<script>
  import aclubMag from './assets/aclub_anime_magazine.jpg'
  import makona from './assets/makona.png'
  import sailormoon from './assets/Sailor_Senshi2.png'
  import smcomics from './assets/sailormoon_comic_books.jpeg'
  import animenano from './assets/animenano.png'
  import usagi from './assets/usagi-sad.gif'
  import blogger from './assets/Blogger-Logo.png'
  import livejournal from './assets/livejournal.webp'
  import onepiece from './assets/onepiece-luffy-wanted.gif'
  import naruto from './assets/naruto_manga.jpg'
  import manga_stuff from './assets/manga-stuff.webp'
  import bleach from './assets/bleach_manga.jpg'
  import opwtf from './assets/piratelickerOPwtf.gif'
  import songs1 from './assets/songs1.png'
  import songs2 from './assets/songs2.png'
</script>

<main class="hero">
  <div class="hero-wrapper">
    <div class="hero-haruhi">
      <h1 class="hero-header">The Melancholy of Hong Kheng</h1>
      <div class="hero-sub">About my own dying hobby of anime/manga fandom in my younger days.</div>
    </div>
    <div class="hero-sub-bg">
    </div>
  </div>
</main> 

<main class="collage">
  <div class="bg-collage">
    <img class="overlap" style="top: 0; left :0;" src={sailormoon} alt="sailormoon" />
    <img class="overlap" style="left: 0; bottom: 0;" src={aclubMag} alt="a-club" />
    <img class="overlap" style="top: 0; left: 600px; right: 0;" width="600" src={smcomics} alt="sm comics" />
  </div>
</main>

<main>
  <div>
    <h1>1998 - 2002</h1>
    <h2>Search the internet for information</h2>
    <p>Didn't get to watch (full) anime episodes or series</p>
    <p>Stick to listening to sound track songs</p>
    <p>Plain oogling at the images</p> 
    <img src={usagi} alt="sad" />
  </div>
</main>

<main>
  <div>
    <h1>2003 - present</h1>
    <h2>THE INTERNET</h2>
    <div class="row">
      <img src={blogger} width="230" alt="blogger" />
      <img src={livejournal} width="250" height="auto" alt="lj" />
    </div>
    <img src={onepiece} alt="wanted" />
  </div>
</main>

<main>
  <img src={naruto} alt="nmanga" />
</main>

<main>
  <img src={bleach} alt="" />
</main>

<main>
  <p>find assorted manga covers</p>
</main>

<main class="collage">
  <img src={manga_stuff} alt="own" width="100%" />
</main>

<main>
  <div>
    <h1>Music!!</h1>
    <div>
      <p>Has about ~~50 gb of <s>downloaded</s> music</p>
      <p>Mostly MP3s with 320kps quality</p>
      <p>Have some in FLAC format</p>
    </div>
    <div class="row">
      <img src={songs1} alt="" width="600"/>
      <img src={songs2} alt="" width="600" />
    </div>
    <div>
      <p>Recently, using Apple Music more</p>
      <p>Not downloading anymore</p>
      <img src={opwtf} alt=""/>
    </div>
  </div>
</main>

<main>
  <div>
    <h1>why?</h1>

  </div>
</main>

<main>
  <div>
  <h1>Credits</h1>
  <img width='200' src={makona} alt="makona" />
  </div>

</main>

<style>
.hero-wrapper {
  position: relative;
  width: 100%;
}

.hero-haruhi {
  margin: 0;
  padding: 0;
  height: 0;
  width: 0;
  border-left: 30vw solid red;
  border-right: 30vw solid transparent;
  border-bottom: 30vw solid transparent;
  border-top: 30vw solid red;
}

.hero-sub-bg {
  position: absolute;
  right: 0;
  bottom: 0;
  background: url('./assets/haruhi-bg.png') no-repeat;
  width: 40%;
  height: 60%;
  color: black;
}

.hero-sub {
  position: absolute;
  color: black;
  top: 45vh;
  left: 4.2em;
  text-align: left;
  font-size: 2rem;
  line-height: 2.5rem;
  width: 50vw;
}

</style>

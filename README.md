# OwsleyTributePage
A tribute page for Owsley Stanley.

See it live on [codepen.io](https://codepen.io/seidobllik/full/xxVpVaK).

Created as a submission for the [freeCodeCamp.org Tribute Page Challenge](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-tribute-page) toward the Responsive Web Design certificate.

<div class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="seidobllik" data-slug-hash="xxVpVaK" data-prefill='{"title":"Owsley Stanley Tribute Page","tags":[],"scripts":[],"stylesheets":[]}'>
  <pre data-lang="html">&lt;head>
  &lt;link href='https://fonts.googleapis.com/css?family=Oswald' rel='stylesheet'>
&lt;/head>
&lt;main id="main">
  &lt;h1 id="title">Owsley Stanley&lt;/h1>
  &lt;p>Augustus Owsley Stanley III (January 19, 1935 – March 12, 2011)&lt;/p>
  &lt;hr>
  &lt;div id="img-div">
    &lt;img id="image" src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.rollingstone.com%2Fwp-content%2Fuploads%2F2018%2F06%2Fgettyimages-480680057-3c360381-3019-4974-820b-4842b191dbd4.jpg&f=1&nofb=1" alt="Owsley Stanley wearing a ragged hat during a festival.">
    &lt;figcaption for="image" id="img-caption">Image of Owsley Stanley in 1975.&lt;/figcaption>
  &lt;/div>
  &lt;section id="tribute-info">
    &lt;p>Owsley Stanley was an American audio engineer and clandestine chemist. He was a key figure in the San Francisco Bay Area hippie movement during the 1960s and played a pivotal role in the decade's counterculture. Under the professional name Bear, he was the soundman for the rock band the Grateful Dead, whom he met when Ken Kesey invited them to an Acid Test party. As their sound engineer, Stanley frequently recorded live tapes behind his mixing board and developed their Wall of Sound sound system, one of the largest mobile public address systems ever constructed. Stanley also designed the band's trademark skull logo.&lt;/p>

    &lt;p>Stanley was the first known private individual to manufacture mass quantities of LSD. By his own account, between 1965 and 1967, Stanley produced no less than 500 grams of LSD, amounting to a little more than five million doses.&lt;/p>

    &lt;p>He died in a car accident in Australia (where he had taken citizenship in 1996) on March 12, 2011.&lt;/p>
    &lt;hr>
    &lt;h3>If you are interested in learning more about &lt;em>Owsley Stanley&lt;/em>, you can continue your research at his &lt;a href="https://en.wikipedia.org/wiki/Owsley_Stanley" id="tribute-link" target="_blank">Wikipedia page&lt;/a>.&lt;/h3>
  &lt;/section>
&lt;/main></pre>
  <pre data-lang="css">html {
  font-size: 10px;
  font-family: Oswald;
}

#main {
  text-align: center;
  font-size: 2rem;
  margin: 2rem 2rem;
  padding: 1rem;
  background: lightgray;
  border-radius: 2rem;
}

h1 {
  font-size: 5rem;
  margin: 0rem;
}

h3 {
  font-size: 2rem;
  text-align: center;
}

#image {
  max-width: 50%;
  max-height: auto;
  border-radius: 1rem;
}

figcaption {
  font-size: 1.5rem;
}

#tribute-info {
  margin: 5rem 10rem;
  font-size: 2rem;
  text-align: left;
}

@media (max-width: 600px) {
  #image {
    max-width: 100%;
  }

  #tribute-info {
    margin: 0rem;
  }
}
</pre></div>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

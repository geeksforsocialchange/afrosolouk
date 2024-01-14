---
layout: default
---

<section>
  <div class="hero__wrapper">
    <div class="hero">
      <div class="content">
        <!-- <h1 class="hero__title narrow">do we need a headline?</h1> -->
      </div>
    </div>
  </div>

  <div class="hero__caption">
    <div class="content">
      <div class="hero__caption-text">
        NBAA led the research via individual life stories and family members' memories of African women and men in Greater Manchester 1920s - 1950s. Utilising where appropriate newspaper articles and recognised search references.
      </div>
    </div>
  </div>

  <div class="content">
    <p class="h2 narrow">Afro Solo UK is the result of 2 years research of the African diaspora of Greater Manchester. Each life story is an act of remembrance, a celebration and in some cases a reconciliation. They provide a legacy and are a declaration that this community will never again be overlooked.</p>
    <p class="btn">
      <a href="#about">Learn more about the project</a>
    </p>
  </div>
  <br>
</section>

<hr>

<section id="participants">
  <div class="content">
    <br>
    <ul class="participants reset">
      {% for participant in site.data.participants %}
        <li class="participant">
          <h3 class="participant__name">{{ participant.name }}</h3>
          <div class="participant__dob">{{ participant.dob }}</div>
          <img src="/assets/participants/{{ participant.photo }}" class="participant__photo" alt="A photo of {{ participant.name }}">
          <div class="participant__caption">{{ participant.caption }}</div>
        </li>
      {% endfor %}
    </ul>
  </div>
  <br><br>
</section>

<section>
  <div class="theme-2">
    <div class="content content--padding">
      <h2 class="narrow">Every picture tells a story. Here are the families' images captured over the years full of memories.</h2>
      {% include youtube.html id='YeWn7wzLJTk' %}
    </div>
    <br>
  </div>
</section>

<section id="performances">
  <div class="theme-3">
    <div class="content content--padding">
      <h1>The launch</h1>
    </div>
  </div>

  <div class="content">
    <p class="h2 narrow">Held at HOME on May 19th 2019, 140 family members joined us for the launch event.</p>

    <div class="photos">
      <img src="/assets/launch/launch1.jpg">
      <img src="/assets/launch/launch2.jpg">
      <img src="/assets/launch/launch3.jpg">
    </div>
    <br>
    <p class="narrow">The event was an afternoon of performances of poetry, dance and song and a unique one-act play scripted verbatim from all the interviews bringing the lives of the mothers live to the stage for a one-off unique performance now captured on film.</p>
    <br>
    <div class="photos">
      <img src="/assets/launch/launch4.jpg">
      <img src="/assets/launch/launch5.jpg">
      <img src="/assets/launch/launch6.jpg">
    </div>
    <br>
    <div class="narrow center">
        <p><em>Please be advised that the play that forms part of this performance reel contains offensive racist language. Such language definitely does not reflect the attitude of NBAA, the actors nor the women they portray but are the actual words that were used to abuse the mothers.</em></p>
      <br>
      {% include youtube.html id='wzTHyhEwmGs' %}
    </div>
    <br>

  </div>
</section>

<section id="book">
  <div class="theme-3">
    <div class="content content--padding">
      <h1>The book</h1>
    </div>
  </div>

  <div class="content">
      <p>TODO: choose blockquote</p>
    <br>
    <blockquote class="x-narrow">
      <p>This collection of stories is about love.</p>
      <p>It is also about hidden lives, sometimes painful, sometimes heart-breaking, always important. The oral histories of relationships across the divides of race and celebrates the ways in which women sustain and support their families over time.</p>
      <p>Like all hidden histories, these stories represent living knowledge that can inform future generations and can help us think differently about the experiences of children from interracial relationships.</p>
    </blockquote>
    <cite>Edited review by Kate Pahl<br>MMU Professor of Arts and Literacy</cite>
    <br><br>
    {% include book.html %}

    <p class="h2 no-bottom-margin">Afro Solo UK </p>
    <p class="center"><strong>ISBN</strong> TODO: is there an isbn?</p>

    <p class="btn">
    <!-- todo: add pdf -->
      <a href="/assets/ASUK.pdf">Download the PDF</a>
    </p>

    <br>
    <!-- todo: are there hard copies? -->

    <p class="x-narrow">
      <strong>Hard copies can only be collected in person from:</strong><br>
      <br>
      Ahmed Iqbal Ullah Race Relations Resource Centre<br>
      Lower Ground Floor<br>
      Central Library<br>
      St Peter’s Square<br>
      Manchester<br>
      M2 5PD<br>
      <br>
      By post email <a href="mailto:contact@ourmothers.org">contact@ourmothers.org</a>
    </p>

  </div>
</section>

<br><br><br>

<hr>

<section id="about">
  <div class="content">
    <br>
    <h1 class="h2">Background on the project</h1>

    <p class="narrow">A total of 78 people were initially approached. Resulting in 39 published life story chapters.</p>

    <p class="narrow">They gave their family histories, photographs, their own life stories to help create this important and unique archive.</p>

    <p class="narrow">A cultural and community history based around the lives of Africans in Greater Manchester from the 1920s to the 1960s...</p>

    <p class="narrow">Afro Solo UK might never have happened had Leslie Johnson not donated a collection of photographs to AIURR. The collection included family snaps, studio portraits and street photographs of the family and friends of Leslie’s parents, Jide and Renee Johnson. What made them special was that they were a visual record of Africans in Manchester in the 1940s. A community that had fallen beneath public awareness as increasingly the “Windrush” has become the timeline for Black communities in the UK.</p>

    <p class="narrow">AIURRRC set the photographs as an exhibition showing it in local libraries and sharing it with African community groups. The photos generated huge interest, stirring up memories and re-capturing the names of numerous people featured.</p>

    <p class="narrow">Leslie was delighted with this response: “It is great to know that some of my old family photos created so much interest, and memories for others to enjoy. I am sure my parents are looking down on me amazed that their pictures, from the bottom drawer of the sideboard could ever have been of interest to anybody else! It feels right to give these memories back, so that the Now and Future may understand.”</p>

    <p class="narrow">Leslie’s photographs form the foundations of the Afro Solo UK research of images and memories of the oft-forgotten African community in Manchester.</p>

    <p class="narrow">ASUK is dedicated to West African Jide (Jimmy) and his Mancunian wife Renee who married in 1947 and raised their family in Hulme, Moss Side and Wythenshawe before they both passed away in 1981</p>

    <p class="narrow">Jackie Ould, AIURR.</p>

!TODO choose an image for here

    <p class="narrow">
      Afro Solo UK Steering Group
      Dr Hakim Adi, BA Hons., PhD
      Dinesh Allirajah, Chair of Trustees NBAA
      Burjor Avari MMU Honorary Research Fellow
      Jackie Ould, AIURRRC
      Paul Okojie MMU, Senior Lecturer in Law
      Rebecca Asgill, Community Activist
    </p>
    <p class="btn">
        <a href="#participants">Back to participants</a>
      </p>

    <br>

    <h1 class="h2">Send us feedback</h1>

    <p class="narrow">Do you have any feedback about the book, the launch, or the project as a whole? Please let us know with the following form.</p>

    <p class="btn">
      <a href="https://forms.gle/Un3S4B9L7zf6Rq4X7">Feedback form</a>
    </p>

  </div>
</section>

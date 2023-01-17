
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Towards Novel View Synthesis from Unconstrained Photo Collections with Cross-Rays Neural Radiance Fields</title>
    <!-- Bootstrap -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  </head>

  <!-- cover -->
  <section>
    <div class="jumbotron text-center mt-0">
      <div class="container" style="margin-bottom:-60px">
        <div class="row">
          <div class="col-12">
            <h2> Towards Novel View Synthesis from Unconstrained Photo Collections with Cross-Rays Neural Radiance Fields</h2>
            <h4 style="color:#5a6268;">ICML 2023</h4>
            <hr>
            <h6> <a href="" target="_blank">A</a><sup>1</sup>, 
                <a href="" target="_blank">B</a><sup>2</sup>,
                <a href="" target="_blank">C</a><sup>2</sup>, 
                <a href="" target="_blank">D</a><sup>1</sup>,
                E</a><sup>2</sup>,
                <a href="" target="_blank">F</a><sup>2</sup>, 
                <a href="" target="_blank">G</a><sup>2</sup></h6>
            <p><sup>1</sup>A &nbsp;&nbsp; 
                <sup>2</sup>B</p>
            <div class="row justify-content-center">
              <div class="column">
                  <p class="mb-5"><a class="btn btn-large btn-dark" href="" role="button"  target="_blank">
                    <ion-icon name="document-text-outline"></ion-icon> Paper</a> </p>
              </div>
              &nbsp;&nbsp;
              <div class="column">
                  <p class="mb-5"><a class="btn btn-large btn-dark" href="" role="button"  target="_blank">
                    <ion-icon name="logo-github"></ion-icon> Code</a> </p>
              </div>
              &nbsp;&nbsp;
              <div class="column">
                  <p class="mb-5"><a class="btn btn-large btn-dark" href="" role="button"  target="_blank">
                    <ion-icon name="document-attach-outline"></ion-icon> Supplementary</a> </p>
              </div>
              &nbsp;&nbsp;
              <div class="column">
                <p class="mb-5"><a class="btn btn-large btn-dark" href="" role="button"  target="_blank">
                  <ion-icon name="document-text-outline"></ion-icon>Poster</a> </p>
            </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- abstract -->
  <section>
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
          <h3>Abstract</h3>
            <hr style="margin-top:0px">
            <img width="100%" src="img/image2.png" alt="picture">
            <!-- <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted=""> -->
                  <!-- <source src="images/image1.png" type="video/mp4"> -->
              <!-- </video> -->
              <!-- <br><br> -->
          <p class="text-justify">  </p>
          <p class="text-justify">Neural Radiance Fields (NeRF) has recently gained popularity for its impressive novel view synthesis ability. This paper studies the problem of hallucinated NeRF: i.e., recovering a realistic NeRF at a different time of day from a group of tourism images. Existing solutions adopt NeRF with a controllable appearance embedding to render novel views under various conditions, but they cannot render view-consistent images with an unseen appearance. To solve this problem, we present an end-to-end framework for constructing a hallucinated NeRF, dubbed as Ha-NeRF. Specifically, we propose an appearance hallucination module to handle time-varying appearances and transfer them to novel views. Considering the complex occlusions of tourism images, we introduce an anti-occlusion module to decompose the static subjects for visibility accurately. Experimental results on synthetic data and real tourism photo collections demonstrate that our method can hallucinate the desired appearances and render occlusion-free images from different views.</p>
        </div>
      </div>
    </div>
  </section>
  <br>

  <section>
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
            <h3>Overview video</h3>
            <hr style="margin-top:0px">
            <div class="embed-responsive embed-responsive-16by9">
                <iframe style="clip-path: inset(1px 1px)" width="100%" height="100%" src="https://www.youtube.com/embed/Qrz0gfcTdQs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
            </div>
        </div>
      </div>
    </div>
  </section>
  <br>

  <!-- Appearsnce Hallucination
  <section>
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
            <h3> Appearance Hallucination of Brandenburg Gate </h3>
            <hr style="margin-top:0px">
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="images/app_Gate_c.mp4" type="video/mp4">
            </video>
        </div>
      </div>
    </div>
  </section>
  <br> of Brandenburg Gate -->

  <!-- Appearance
  <section>
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
            <h3>Appearance Hallucination of Brandenburg Gate</h3>
            <hr style="margin-top:0px">
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="images/app_Gate_c.mp4" type="video/mp4">
            <h3>Appearance Hallucination of Trevi Fountain</h3>
            <hr style="margin-top:0px">
            </video>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="images/app_Fountain_c.mp4" type="video/mp4">
            </video>
        </div>
      </div>
    </div>
  </section>
  <br> Hallucination -->

  <!-- Appearance Hallucination -->
  <section>
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
            <h3>Appearance Hallucination</h3>
            <hr style="margin-top:0px">
            <h4 style="margin-top:20px; margin-bottom:20px; color:#717980">Brandenburg Gate</h4>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="images/app_Gate_c.mp4" type="video/mp4">
            </video>
            <h4 style="margin-top:20px; margin-bottom:20px; color:#717980">Trevi Fountain</h4>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="images/app_Fountain_c.mp4" type="video/mp4">
            </video>
        </div>
      </div>
    </div>
  </section>
  <br>

  <!-- Cross-Appearance Hallucination -->
  <section>
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
            <h3>Cross-Appearance Hallucination</h3>
            <hr style="margin-top:0px">
            <h4 style="margin-top:20px; margin-bottom:20px; color:#717980">From Trevi Fountain to Brandenburg Gate</h4>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="images/Fountain2Gate_c.mp4" type="video/mp4">
            </video>
            <h4 style="margin-top:20px; margin-bottom:20px; color:#717980">From Brandenburg Gate to Trevi Fountain</h4>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="images/Gate2Fountain_c.mp4" type="video/mp4">
            </video>
        </div>
      </div>
    </div>
  </section>
  <br>

  <!-- Appearance Hallucination From Artworks -->
  <section>
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
            <h3>Appearance Hallucination From Artworks</h3>
            <hr style="margin-top:0px">
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="images/art_c.mp4" type="video/mp4">
            </video>
        </div>
      </div>
    </div>
  </section>
  <br>

  <!-- citing -->
  <div class="container">
    <div class="row ">
      <div class="col-12">
          <h3>Citation</h3>
          <hr style="margin-top:0px">
              <pre style="background-color: #e9eeef;padding: 1.25em 1.5em">
<code>@inproceedings{
}</code></pre>
          <hr>
      </div>
    </div>
  </div>

  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>
</html>

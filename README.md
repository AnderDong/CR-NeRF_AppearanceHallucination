
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
      <div class="container">
        <div class="row">
          <div class="col-12">
            <h2> Towards Novel View Synthesis from Unconstrained Photo Collections with Cross-Rays Neural Radiance Fields</h2>
            <!-- <h4 style="color:#5a6268;">ICML 2023</h4> -->
            <!-- <hr>
            <h6> <a href="" target="_blank">A</a><sup>1</sup>, 
                <a href="" target="_blank">B</a><sup>2</sup>,
                <a href="" target="_blank">C</a><sup>2</sup>, 
                <a href="" target="_blank">D</a><sup>1</sup>,
                </a><sup>2</sup>,
                <a href="" target="_blank">F</a><sup>2</sup>, 
                <a href="" target="_blank">G</a><sup>2</sup></h6>
            <p><sup>1</sup>A &nbsp;&nbsp; 
                <sup>2</sup>B</p>
            <div class="row justify-content-center">
              <div class="column">
                  <p class="mb-5"><a class="btn btn-large btn-dark" href="baidu.com" role="button"  target="_blank">
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
                  <ion-icon name="document-text-outline"></ion-icon>Poster</a> </p> -->
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
            <img width="100%" src="img/overview.jpg" alt="picture">
            <!-- <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted=""> -->
                  <!-- <source src="images/image1.png" type="video/mp4"> -->
              <!-- </video> -->
              <!-- <br><br> -->
          <p class="text-justify">  </p>
          <p class="text-justify">Neural Radiance Fields (NeRF) has facilitated recent advances due to its impressive capabilities in novel view synthesis. In this paper, we study recovering a realistic NeRF by reconstructing images from unconstrained photo collections. Although the images are abundant and easily available, reconstructing these images presents two challenges due to the static-scene limitation of NeRF: (1) the images have variable appearance due to different capturing time and camera settings; (2) the images contain transient objects like humans and cars. Existing methods address the challenges by considering local information of each single ray of a scene independently. We theoretically analyze that considering correlation across multiple rays promotes capturing more global information. Motivated by this, we propose a Cross-Ray paradigm that processes multiple rays simultaneously. Based on the paradigm, we propose a Cross-Ray NeRF (CR-NeRF). Specifically, we represent multiple rays with a novel cross-ray feature and recover the appearance by fusing global statistics, i.e.,feature covariance of the rays and appearance of the images. Moreover, we develop the perspective of transient objects handling as image segmentation on multiple rays, through which we segment and grid sample the images for a visibility map regarding rays of the objects. Experimental results on large real-world datasets verify the effectiveness of CR-NeRF. CR-NeRF also allows for efficient inference of arbitrary appearance modeling and synthesis of non-transient images from multiple views.</p>
        </div>
      </div>
    </div>
  </section>
  <br>

  <section>
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
            <h3>Appearance Hallucination</h3>
            <hr style="margin-top:0px">
            <h4 style="margin-top:20px; margin-bottom:20px; color:#717980">Brandenburg Gate</h4>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="video/video1.mp4">
            </video>
            <h4 style="margin-top:20px; margin-bottom:20px; color:#717980">Trevi Fountain</h4>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="video/video2.mp4">
            </video>
            </video>
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
  <!-- <section>
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
            <h3>Appearance Hallucination</h3>
            <hr style="margin-top:0px">
            <h4 style="margin-top:20px; margin-bottom:20px; color:#717980">Brandenburg Gate</h4>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="video/video3.mp4">
            </video>
            <h4 style="margin-top:20px; margin-bottom:20px; color:#717980">Trevi Fountain</h4>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="video/video4.mp4">
            </video>
            </video>
        </div>
      </div>
    </div>
  </section>
  <br> -->

  <!-- Cross-Appearance Hallucination -->
  <section>
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
            <h3>Cross-Appearance Hallucination</h3>
            <hr style="margin-top:0px">
            <h4 style="margin-top:20px; margin-bottom:20px; color:#717980">From Trevi Fountain to Brandenburg Gate</h4>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="video/thime.mp4">
            </video>
            <h4 style="margin-top:20px; margin-bottom:20px; color:#717980">From Brandenburg Gate to Trevi Fountain</h4>
            <video width="100%" playsinline="" autoplay="autoplay" loop="loop" preload="" muted="">
                <source src="video/thime.mp4">
            </video>
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
                <source src="video/video5.mp4">
            </video>
        </div>
      </div>
    </div>
  </section>
  <br>

  <!-- citing -->
  <!-- <div class="container">
    <div class="row ">
      <div class="col-12">
          <h3>Citation</h3>
          <hr style="margin-top:0px">
              <pre style="background-color: #e9eeef;padding: 1.25em 1.5em">
<code>@inproceedings{
}</code> -->

</pre>
          <hr>
      </div>
    </div>
  </div>

  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>
</html>

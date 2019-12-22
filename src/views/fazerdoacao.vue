<template>
  <Principal>
    <div>
      <div
        class="Wrapper_wrapper__28JZg BlockContentHtml_wrapper__3bo2x Wrapper_wrapper-default-width__2PRux"
        style="background-image: url(&quot;undefined&quot;);"
      >
        <div class="Wrapper_container__3c3aY Wrapper_container-default-width__2lKTA">
          <div class="HtmlMarkup_html__3sUPP">
            <!-- <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <meta http-equiv="X-UA-Compatible" content="ie=edge">-->
            <link
              href="https://css.rede.natura.net/html/novosite20180716/natura-style/assets/css/natura-style-core.css"
              rel="stylesheet"
            />
            <link
              href="https://css.rede.natura.net/html/novosite20180716/natura-style/assets/css/natura-style-custom.css"
              rel="stylesheet"
              type="text/css"
            />
            <div id="page-custom">
              <div class="container max-center">
                <div class="row">
                  <div class="col-md-12">
                    <h1 class="title-line-center">INSTITUIÇÕES</h1>
                  </div>
                </div>

                <div class="row">
                  <div class="col-md-12">
                    <p
                      class="text-center"
                    >Estas são as Instituições que fazem parte do projeto Gaia.</p>
                  </div>
                </div>
              </div>

              <div class="container">
                <div class="row">
                  <div class="col-md-3 col-sm-6 text-center container-lines">
                    <div class="container-lines">
                      
                      
                      <div
                        class="img-line"
                        style="background-image: url('https://secureservercdn.net/198.71.233.254/100.fc5.myftpupload.com/wp-content/uploads/2019/04/image2_15.png" alt="" width="782" height="262" srcset="https://secureservercdn.net/198.71.233.254/100.fc5.myftpupload.com/wp-content/uploads/2019/04/image2_15.png 782w, https://secureservercdn.net/198.71.233.254/100.fc5.myftpupload.com/wp-content/uploads/2019/04/image2_15-300x101.png 300w, https://secureservercdn.net/198.71.233.254/100.fc5.myftpupload.com/wp-content/uploads/2019/04/image2_15-768x257.png 768w')"
                       
                      >&nbsp;</div>
                    
                      
                      
                      
                      
                      
                      
                      <h2>
                        <a class="title-lines" href="/tododia">
                          <span class="lines">TodoDia</span>
                        </a>
                      </h2>
                    </div>
                  </div>
                  
                  <div class="col-md-3 col-sm-6 text-center">
                    <div class="container-lines">
                      <div
                        class="img-line"
                        style="background-image: url('https://static.rede.natura.net/html/novosite20180716/natura-style/img/marcas/marca-kaiak.jpg')"
                      >&nbsp;</div>

                      <h2>
                        <a class="title-lines" href="/kaiak">
                          <span class="lines">Kaiak</span>
                        </a>
                      </h2>
                    </div>
                  </div>

                  <div class="col-md-3 col-sm-6 text-center container-lines">
                    <div class="container-lines">
                      <div
                        class="img-line"
                        style="background-image: url('https://static.rede.natura.net/html/2019/nossas_marcas/essencial.jpg')"
                      >&nbsp;</div>

                      <h2>
                        <a class="title-lines" href="/essencial">
                          <span class="lines">Essencial</span>
                        </a>
                      </h2>
                    </div>
                  </div>

                  <div class="col-md-3 col-sm-6 text-center container-lines">
                    <div class="container-lines">
                      <div
                        class="img-line"
                        style="background-image: url('https://static.rede.natura.net/html/2019/nossas_marcas/ekos.jpg')"
                      >&nbsp;</div>

                      <h2>
                        <a class="title-lines" href="/ekos">
                          <span class="lines">Ekos</span>
                        </a>
                      </h2>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </Principal>
</template>

<script>
import Principal from "../layouts/principal";

export default {
  name: "app",
  components: { Principal }
};
</script>

<style>
#page-custom h2 {
  font-weight: 300;
}
#page-custom .container-lines,
#page-custom .img-line {
  position: relative;
  height: 27.5rem;
  margin-bottom: 30px;
}
#page-custom .container-lines:hover {
  top: -1px;
  transition: all 3s ease;
}

#page-custom .img-line {
  background-position-x: center;
  background-repeat: no-repeat;
}
#page-custom .title-lines {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  margin: 0;
  background-color: rgba(0, 0, 0, 0.4);
  color: #fff;
  font-size: 1.375rem;
  text-transform: uppercase;
  font-weight: 600;
}
#page-custom .title-lines:hover {
  color: #fff;
}
#page-custom .lines {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
</style>

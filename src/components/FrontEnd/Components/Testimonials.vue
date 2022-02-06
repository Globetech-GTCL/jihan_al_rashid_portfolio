<template>
  <div class="hello">
      <section class="section" id="testimonials">
      <div class="container">
        <div class="row">
            <div class="col-lg-8 offset-lg-2">
                <div class="center-heading">
                    <h2>My <em>Team</em></h2>
                    <p>I have also an expert team where they contribute their skill to attain my goal.</p>
                </div>
            </div>
            <div class="col-lg-10 col-md-12 col-sm-12 mobile-bottom-fix-big">
                <!-- <h1>This is very good</h1> -->
                <carousel :items="3" :margin="10" :nav="false" :dots="true" :loop="true" 
                    :responsive="{
                        0: {
                            items: 1
                        },
                        600: {
                            items: 1
                        },
                        1000: {
                            items: 2
                        }
                    }"
                >
                    <!-- <img v-for="(img, index) in images" :src="img" :key="index"> -->
                    <div class="item service-item">
                      <div class="author">
                          <i><img src="../../../../public/assets/images/testimonial-author-1.png" alt="Author One"></i>
                      </div>
                      <div class="testimonial-content">
                          <ul class="stars">
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                          </ul>
                          <h4>Sheikh Farukuzzaman</h4>
                          <p>“Nullam hendrerit, elit a semper pharetra, ipsum nibh tristique tortor, in tempus
                              urna elit in mauris.”</p>
                          <span>Senior Software Developer</span> <br>
                          <span> <b>Globetech Company Limited</b> </span>
                      </div>
                    </div>
                    <div class="item service-item">
                      <div class="author">
                          <i><img src="../../../../public/assets/images/testimonial-author-2.png" alt="Author One"></i>
                      </div>
                      <div class="testimonial-content">
                          <ul class="stars">
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                          </ul>
                          <h4>Sheikh Farukuzzaman</h4>
                          <p>“Nullam hendrerit, elit a semper pharetra, ipsum nibh tristique tortor, in tempus
                              urna elit in mauris.”</p>
                          <span>Senior Software Developer</span> <br>
                          <span> <b>Globetech Company Limited</b> </span>
                      </div>
                    </div>
                    <div class="item service-item">
                      <div class="author">
                          <i><img src="../../../../public/assets/images/testimonial-author-3.png" alt="Author One"></i>
                      </div>
                      <div class="testimonial-content">
                          <ul class="stars">
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                          </ul>
                          <h4>Sheikh Farukuzzaman</h4>
                          <p>“Nullam hendrerit, elit a semper pharetra, ipsum nibh tristique tortor, in tempus
                              urna elit in mauris.”</p>
                          <span>Senior Software Developer</span> <br>
                          <span> <b>Globetech Company Limited</b> </span>
                      </div>
                    </div>
                    <div class="item service-item">
                      <div class="author">
                          <i><img src="../../../../public/assets/images/testimonial-author-4.png" alt="Author One"></i>
                      </div>
                      <div class="testimonial-content">
                          <ul class="stars">
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                          </ul>
                          <h4>Sheikh Farukuzzaman</h4>
                          <p>“Nullam hendrerit, elit a semper pharetra, ipsum nibh tristique tortor, in tempus
                              urna elit in mauris.”</p>
                          <span>Senior Software Developer</span> <br>
                          <span> <b>Globetech Company Limited</b> </span>
                      </div>
                    </div>
                </carousel>
            </div>
            <!-- <div class="col-lg-10 col-md-12 col-sm-12 mobile-bottom-fix-big"
                data-scroll-reveal="enter left move 30px over 0.6s after 0.4s">
                <div class="owl-carousel owl-theme">
                    <div class="item service-item">
                      <div class="author">
                          <i><img src="../../../../public/assets/images/testimonial-author-1.png" alt="Author One"></i>
                      </div>
                      <div class="testimonial-content">
                          <ul class="stars">
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                              <li><i class="fa fa-star"></i></li>
                          </ul>
                          <h4>Sheikh Farukuzzaman</h4>
                          <p>“Nullam hendrerit, elit a semper pharetra, ipsum nibh tristique tortor, in tempus
                              urna elit in mauris.”</p>
                          <span>Senior Software Developer</span> <br>
                          <span> <b>Globetech Company Limited</b> </span>
                      </div>
                    </div>
                    <div class="item service-item">
                        <div class="author">
                            <i><img src="../../../../public/assets/images/testimonial-author-2.png" alt="Second Author"></i>
                        </div>
                        <div class="testimonial-content">
                            <ul class="stars">
                                <li><i class="fa fa-star"></i></li>
                                <li><i class="fa fa-star"></i></li>
                                <li><i class="fa fa-star"></i></li>
                                <li><i class="fa fa-star"></i></li>
                                <li><i class="fa fa-star"></i></li>
                            </ul>
                            <h4>Masud Rana</h4>
                            <p>“Morbi non mi luctus felis molestie scelerisque. In ac libero viverra, placerat est
                                interdum, rhoncus leo.”</p>
                            <span> Software Developer</span> <br>
                            <span> <b>Globetech Company Limited</b> </span>
                        </div>
                    </div>
                    <div class="item service-item">
                        <div class="author">
                            <i><img src="../../../../public/assets/images/testimonial-author-3.png" alt="Author Third"></i>
                        </div>
                        <div class="testimonial-content">
                            <ul class="stars">
                                <li><i class="fa fa-star"></i></li>
                                <li><i class="fa fa-star"></i></li>
                                <li><i class="fa fa-star"></i></li>
                            </ul>
                            <h4>Mahbubur Rahman</h4>
                            <p>“Fusce rutrum in dolor sit amet lobortis. Ut at vehicula justo. Donec quam dolor,
                                congue a fringilla sed, maximus et urna.”</p>
                            <span>Senior Software Developer</span> <br>
                            <span> <b>Globetech Company Limited</b> </span>
                        </div>
                    </div>
                    <div class="item service-item">
                        <div class="author">
                            <i><img src="../../../../public/assets/images/testimonial-author-4.png" alt="Fourth Author"></i>
                        </div>
                        <div class="testimonial-content">
                            <ul class="stars">
                                <li><i class="fa fa-star"></i></li>
                                <li><i class="fa fa-star"></i></li>
                                <li><i class="fa fa-star"></i></li>
                                <li><i class="fa fa-star"></i></li>
                            </ul>
                            <h4>Saiful Islam</h4>
                            <p>"Fusce rutrum in dolor sit amet lobortis. Ut at vehicula justo. Donec quam dolor,
                                congue a fringilla sed, maximus et urna."</p>
                            <span>Graphics Designer</span> <br>
                            <span> <b>Globetech Company Limited</b> </span>
                        </div>
                    </div>
                </div>
            </div> -->
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import carousel from 'vue-owl-carousel'
export default {
    components: { carousel },
    name: 'HelloWorld',
    data: function() {
        return {
        images: [
            "https://placeimg.com/200/200/any?1",
            "https://placeimg.com/200/200/any?2",
            "https://placeimg.com/200/200/any?3",
            "https://placeimg.com/200/200/any?4"
        ]
        };
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

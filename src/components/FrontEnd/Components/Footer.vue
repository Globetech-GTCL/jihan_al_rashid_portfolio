<template>
  <div class="hello">
    <footer id="contact-us">
      <div class="container">
          <div class="footer-content">
              <div class="row">
                  <div class="col-lg-6 col-md-12 col-sm-12">
                      <div class="contact-form">
                          <form id="contact" action="" method="post">
                              <div class="row">
                                  <div class="col-md-6 col-sm-12">
                                      <fieldset>
                                          <input name="name" type="text" id="name" placeholder="Full Name" required=""
                                              style="background-color: rgba(250,250,250,0.3);">
                                      </fieldset>
                                  </div>
                                  <div class="col-md-6 col-sm-12">
                                      <fieldset>
                                          <input name="email" type="text" id="email" placeholder="E-Mail Address"
                                              required="" style="background-color: rgba(250,250,250,0.3);">
                                      </fieldset>
                                  </div>
                                  <div class="col-lg-12">
                                      <fieldset>
                                          <textarea name="message" rows="6" id="message" placeholder="Your Message"
                                              required="" style="background-color: rgba(250,250,250,0.3);"></textarea>
                                      </fieldset>
                                  </div>
                                  <div class="col-lg-12">
                                      <fieldset>
                                          <button type="submit" id="form-submit" class="main-button">Send 
                                              Now</button>
                                      </fieldset>
                                  </div>
                              </div>
                          </form>
                      </div>
                  </div>
                  <div class="right-content col-lg-6 col-md-12 col-sm-12">
                      <h2>More About <em>Mr. Jihan</em></h2>
                      <p> <b>Email: </b> <a href="mailto:jihanrashidspandanit@gmail.com">jihanrashidspandanit@gmail.com</a>.<br>
                          <br><b>Phone: </b> <a href="tel:+8801-324 171 586">+8801-324 171 586</a>
                          <br><br>If you want to contact me, you may follow my <a
                              rel="nofollow" href="https://facebook.com/jihan.al.rashid" target="_parent">Facebook</a> 
                          for more detail.</p>
                      <ul class="social">
                          <li><a href="https://www.facebook.com/jihan.al.rashid"><i class="fa fa-facebook"></i></a></li>
                          <li><a href="#"><i class="fa fa-twitter"></i></a></li>
                          <li><a href="https://www.linkedin.com/in/jihan-al-rashid-95068b219"><i class="fa fa-linkedin"></i></a></li>
                          <li><a href="#"><i class="fa fa-rss"></i></a></li>
                          <li><a href="#"><i class="fa fa-dribbble"></i></a></li>
                      </ul>
                  </div>
              </div>
          </div>
          <div class="row">
              <div class="col-lg-12">
                  <div class="sub-footer">
                    <p> Designed & Developed by <a rel="nofollow" href="https://jihanalrashid.com">Jihan Al Rashid</a></p>
                  </div>
              </div>
          </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
//   props: {
//     msg: String
//   }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

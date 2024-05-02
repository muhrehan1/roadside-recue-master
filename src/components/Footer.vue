<template>
  <div class="footer-widget">
    <div class="container">
      <div class="col_full">
        <h2 class="text-center">Let’s stay connected</h2>
        <div class="newsletter">
          <form class="news_form" action="" method="Post">
            <div class="field">
              <input class="form-control" type="email" name="email" placeholder="Your Email" required>
            </div>
            <div class="text-center">
              <input type="submit" name="submit" class="btn-custom" value="Subscribe">
            </div>
          </form>
        </div>
      </div>
      <div class="row">
        <div class="col-12 col-md-4">
          <div class="widget">
            <h3>Roadside rescue</h3>
            <p class="ft-18">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod.</p>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="widget">
            <h3>Quick links</h3>
            <ul>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">About Us</a>
              </li>
              <li>
                <a href="#">Services</a>
              </li>
              <li>
                <a href="#">Book a Service</a>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="widget">
            <h3>Contact us</h3>
            <ul>
              <li>
                <a href="tel:(123-456-789)">123-456-789</a>
              </li>
              <li>
                <a href="mailto:(info@yourcompany.com)">info@yourcompany.com</a>
              </li>
              <li>
                <a href="#">0000 west ryan dr. savannah,aa 0000</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>

  <footer class="footer">
    <div class="container">
      <div class="site-info">
        Copyright © 2024 <a href="#">ROADSIDE RESCUE</a>. All Rights Reserved
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style scoped>
</style>

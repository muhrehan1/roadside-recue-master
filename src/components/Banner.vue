<template>
    <section class="secBanner" style="background-image: url('/images/bg_banner.jpg');">
        <div class="container">
            <div class="row">
                <div class="col-12 col-md-7">
                    <div class="info">
                        <h1 class="vc_banner">Your Roadside Rescue<br> Team</h1>
                        <p class="ft-18">Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed<br> diam nonumy eirm tempor Invidunt.</p>
                    </div>
                    <div class="bn_form">
                        <form action="" class="form" method="post">
                            <div class="field loct"><input class="form-control" name="location" type="text" placeholder="Enter your address" required></div>
                            <div class="field srv"><select class="form-control" name="serv"><option>Choose a service</option><option>Service 1</option><option>Service 2</option><option>Service 3</option><option>Service 5</option><option>Service 6</option></select></div>
                            <p><input class="btn_bn" name="submit" type="submit" value="Search"></p>
                        </form>
                    </div>
                </div>
                <div class="col-12 col-md-5">
                    <div class="bn_img">
                        <img src="../../public/images/vector.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
  export default {
    name: 'Banner',
  }
</script>

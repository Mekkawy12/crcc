<template>
  <footer class="py-5" id="footer-main">
    <div class="container">
      <div class="row align-items-center justify-content-xl-between">
        <!--          <div class="col-xl-6">-->
        <!--            <ul class="nav nav-footer">-->
        <!--              <li class="nav-item">-->
        <!--                <a-->
        <!--                  href="https://www.creative-tim.com"-->
        <!--                  class="nav-link"-->
        <!--                  target="_blank"-->
        <!--                  rel="noopener"-->
        <!--                  >CREATIVE TIM</a-->
        <!--                >-->
        <!--              </li>-->
        <!--              <li class="nav-item">-->
        <!--                <a-->
        <!--                  href="https://www.updivision.com"-->
        <!--                  class="nav-link"-->
        <!--                  target="_blank"-->
        <!--                  rel="noopener"-->
        <!--                  >UPDIVISION</a-->
        <!--                >-->
        <!--              </li>-->
        <!--              <li class="nav-item">-->
        <!--                <a-->
        <!--                  href="https://www.creative-tim.com/presentation"-->
        <!--                  class="nav-link"-->
        <!--                  target="_blank"-->
        <!--                  rel="noopener"-->
        <!--                  >ABOUT US</a-->
        <!--                >-->
        <!--              </li>-->
        <!--              <li class="nav-item">-->
        <!--                <a-->
        <!--                  href="http://blog.creative-tim.com"-->
        <!--                  class="nav-link"-->
        <!--                  target="_blank"-->
        <!--                  rel="noopener"-->
        <!--                  >BLOG</a-->
        <!--                >-->
        <!--              </li>-->
        <!--              <li class="nav-item">-->
        <!--                <a-->
        <!--                  href="https://www.creative-tim.com/license"-->
        <!--                  class="nav-link"-->
        <!--                  target="_blank"-->
        <!--                  rel="noopener"-->
        <!--                  >LICENSES</a-->
        <!--                >-->
        <!--              </li>-->
        <!--            </ul>-->
        <!--          </div>-->
        <div class="col-xl-8 pr-1">
          <div class="copyright text-center text-lg-right text-muted">
            © {{ year }}, all rights reserved to the project maintainers
            <!--              <i class="fa fa-heart heart"></i> by<a-->
            <!--                href="https://www.creative-tim.com"-->
            <!--                class="font-weight-bold ml-1"-->
            <!--                target="_blank"-->
            <!--                rel="noopener"-->
            <!--                >Creative Tim</a-->
            <!--              >-->
            <!--              and-->
            <!--              <a-->
            <!--                href="https://www.updivision.com"-->
            <!--                class="font-weight-bold ml-1"-->
            <!--                target="_blank"-->
            <!--                rel="noopener"-->
            <!--                >UPDIVISION</a-->
            <!--              >-->
            <!--              for a better web.-->
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style></style>

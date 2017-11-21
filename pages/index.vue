<template>
  <div class="flex flex-column min-vh-100">
    <div class="background absolute h-100 left-0 w-50" style="background: url(/images/pattern.png);">
      <!-- <img src="images/pattern.png"> -->
    </div>
  	<div class="center mt4 pt3">
  		<kono-logo :height="40" :width="50"></kono-logo>
  	</div>
  	<div class="flex-auto flex flex-column justify-center z-3 ph3">
  		<div class="mw7 center f2-ns f4">
  			<h1 class="fw9 tc lh-title-ns mv0 pb4 ">A human to human design agency.</h1>
  			<p class="tc f3-ns f4 ph4 lh-copy-ns mv0" style="font-family: Calibre !important">At Kono, we design for the little guys: thumbs, fingers, and eyeballs. We create thoughtful digital experiences and build unmistakable brands.</p>
  			<div class="w-30-ns w-70 center mt5-ns mt4">
  				<a href="" class="no-underline fw5 f4-ns f5 br-pill tc db btn" style="font-family: Calibre !important;">LET'S TALK</a>
  			</div>
  		</div>
  	</div>
    <div class="center mb4 mt0">
      <p style="font-family: Calibre !important; font-size: 18px;">&copy; Kono, Inc. 2017</p>
    </div>
  </div>
</template>

<script>
import KonoLogo from '~/components/KonoLogo.vue'

export default {
  components: {
    KonoLogo,
  },
  head() {
    return {
      title: 'Kono | Human to human design agency.',
      meta: [{
        hid: 'Home',
        name: 'Home',
        content: 'Kono homepage splashscreen'
      }]
    }
  }
}
</script>

<style>
  .background {
    opacity: .2;
    background-size: 15px !important;
    z-index: 0;
  }
  .lh-title {
    line-height: 80px;
  }
  .lh-copy {
    line-height: 34px;
  }
  .btn {
    background-color: white;
    padding-top: 20px;
    padding-bottom: 10px;
    -webkit-box-shadow: 0 6px 15px #f0f0f0;
    -moz-box-shadow: 0 6px 15px #f0f0f0;
    box-shadow: 0 6px 15px #f0f0f0;
    transition: all 250ms cubic-bezier(.02, .01, .47, 1)
  }
  .btn:hover {
    -webkit-box-shadow: 0 8px 15px #ebebeb;
    -moz-box-shadow: 0 8px 15px #ebebeb;
    box-shadow: 0 8px 15px #ebebeb;
  }
</style>
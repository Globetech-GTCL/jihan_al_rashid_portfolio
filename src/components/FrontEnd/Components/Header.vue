<template>
  <div class="hello">
    <header class="header-area header-sticky">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <nav class="main-nav">
                        <a href="index.html" class="logo">
                        <img src="../../../../public/assets/images/logo-main.png">
                        </a>
                        <ul class="nav">
                            <li class="scroll-to-section"><a href="#welcome" class="menu-item">Home</a></li>
                            <li class="scroll-to-section"><a href="#about" class="menu-item">About</a></li>
                            <li class="scroll-to-section"><a href="#testimonials" class="menu-item">My Team</a>
                            </li>
                            <!-- <li class="submenu">
                                <a href="javascript:;">More</a>
                                <ul>
                                    <li><a href="" class="menu-item">About Me</a></li>
                                    <li><a href="" class="menu-item">Features</a></li>
                                    <li><a href="" class="menu-item">FAQ's</a></li>
                                    <li><a href="" class="menu-item">Blog</a></li>
                                </ul>
                            </li> -->
                            <li class="scroll-to-section"><a href="#contact-us" class="menu-item">Contact Us</a></li>
                        </ul>
                        <a class='menu-trigger'>
                            <span>Menu</span>
                        </a>
                    </nav>
                </div>
            </div>
        </div>
    </header>
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

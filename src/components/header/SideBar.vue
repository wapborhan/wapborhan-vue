<template>
  <div class="d-none d-xl-block header-style-2">
    <header class="rn-header-area d-flex align-items-start flex-column left-header-style">
      <div class="logo-area">
        <a href="index.html">
          <img src="https://wapborhan.com/images/logo/logo-06.png" alt="WapBorhan-logo" />
        </a>
      </div>
      <nav id="sideNavs" class="mainmenu-nav navbar-example2">
        <ul class="primary-menu nav nav-pills">
          <li class="nav-item">
            <a class="nav-link smoth-animation-two" activeClass="active" to="home" spy={true} smooth={true}>
              <i>
                <FiHome />
              </i>
              Home
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link smoth-animation-two" activeClass="active" to="about" spy={true} smooth={true}>
              <i>
                <FiUser />
              </i>
              About
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link smoth-animation-two" activeClass="active" to="features" spy={true} smooth={true}>
              <i>
                <FiBriefcase />
              </i>
              Features
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link smoth-animation-two" activeClass="active" to="portfolio" spy={true} smooth={true}>
              <i>
                <FiLayers />
              </i>
              Portfolio
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link smoth-animation-two" activeClass="active" to="whyme" spy={true} smooth={true}>
              <i>
                <FiUsers />
              </i>
              Why Me
            </a>
          </li>
          <!-- {/* <li class="nav-item">
            <a class="nav-link smoth-animation-two" href="#pricing">
              <i>
                <FiShoppingCart />
              </i>
              Pricing
            </a>
          </li> */} -->
          <li class="nav-item">
            <a class="nav-link smoth-animation-two" activeClass="active" to="blog" spy={true} smooth={true}>
              <i>
                <FiImage />
              </i>
              blog
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link smoth-animation-two" activeClass="active" to="testimonial" spy={true} smooth={true}>
              <i>
                <FiMessageSquare />
              </i>
              Testimonial
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link smoth-animation-two" activeClass="active" to="contacts" spy={true} smooth={true}>
              <i>
                <FiMessageCircle />
              </i>
              Contact
            </a>
          </li>
        </ul>
      </nav>
      <div class="footer">
        <div class="social-share-style-1  mt--30">
          <span class="title">find with me</span>
          <ul class="social-share d-flex liststyle">
            <li class="facebook">
              <a href="http://www.facebook.com/wapborhan" target="_blank" rel="noopener noreferrer">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                  stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round"
                  class="feather feather-facebook">
                  <path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path>
                </svg>
              </a>
            </li>
            <li class="instagram">
              <a href="https://www.github.com/wapborhan" target="_blank" rel="noopener noreferrer">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                  stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round">
                  <path
                    d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z" />
                </svg>
              </a>
            </li>
            <li class="linkedin" target="_blank" rel="noopener noreferrer">
              <a href="https://www.linkedin.com/in/wapborhan/">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                  stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round"
                  class="feather feather-github">
                  <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
                  <rect x="2" y="9" width="4" height="12"></rect>
                  <circle cx="4" cy="4" r="2"></circle>
                </svg>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'SideBar',
  components: {

  }
}
</script>

<style lang="scss" scoped>
</style>
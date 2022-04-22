<template>
  <div class="header-one">
    <div class="site-navigation">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <nav class="navbar navbar-expand-lg navbar-dark p-0">
              <button
                class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target=".navbar-collapse"
                aria-controls="navbar-collapse"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-icon"></span>
              </button>

              <div id="navbar-collapse" class="collapse navbar-collapse">
                <ul class="nav navbar-nav mr-auto">
                  <li class="nav-item active">
                    <a class="nav-link" href="/">Home</a>
                  </li>

                  <!-- <li class="nav-item dropdown">
                    <a
                      href="#"
                      class="nav-link dropdown-toggle"
                      data-toggle="dropdown"
                      >Company <i class="fa fa-angle-down"></i
                    ></a>
                    <ul class="dropdown-menu" role="menu">
                      <li><a href="about.html">About Us</a></li>
                      <li><a href="team.html">Our People</a></li>
                      <li><a href="testimonials.html">Testimonials</a></li>
                      <li><a href="faq.html">Faq</a></li>
                      <li><a href="pricing.html">Pricing</a></li>
                    </ul>
                  </li> -->

                  <li class="nav-item dropdown">
                    <a
                      href="#"
                      class="nav-link dropdown-toggle"
                      data-toggle="dropdown"
                    >
                      Air Ticket Booking <i class="fa fa-angle-down"></i
                    ></a>
                    <ul class="dropdown-menu" role="menu">
                      <li>
                        <a href="internationalticket"
                          >International Air Ticket</a
                        >
                      </li>
                      <li>
                        <a href="domesticticket">Domestic Air Ticket</a>
                      </li>
                    </ul>
                  </li>

                  <li class="nav-item dropdown">
                    <a
                      href="#"
                      class="nav-link dropdown-toggle"
                      data-toggle="dropdown"
                      >Visa Proccessing <i class="fa fa-angle-down"></i
                    ></a>
                    <ul class="dropdown-menu" role="menu">
                      <li class="dropdown-submenu">
                        <a
                          href="#!"
                          class="dropdown-toggle"
                          data-toggle="dropdown"
                          >Saudia Arabia</a
                        >
                        <ul class="dropdown-menu">
                          <li><a href="#!">Amel Visa</a></li>
                          <li><a href="#!">House Driver Visa</a></li>
                          <li><a href="#!">House Laborer Visa</a></li>
                          <li><a href="#!">Family Visit Visa</a></li>
                          <li><a href="#!">Business Visit Visa</a></li>
                          <li><a href="#!">Umra Visa</a></li>
                          <li><a href="#!">Hazz Visa</a></li>
                        </ul>
                      </li>
                       <li class="dropdown-submenu">
                        <a
                          href="#!"
                          class="dropdown-toggle"
                          data-toggle="dropdown"
                          >Malaysia</a
                        >
                        <ul class="dropdown-menu">
                          <li><a href="#!">Work Visa</a></li>
                          <li><a href="#!">Visit Visa</a></li>
                          <li><a href="#!">Business Visa</a></li>
                          <li><a href="#!">Student Visit Visa</a></li>
                        </ul>
                      </li>
                       <li class="dropdown-submenu">
                        <a
                          href="#!"
                          class="dropdown-toggle"
                          data-toggle="dropdown"
                          >UAE/Dubai</a
                        >
                        <ul class="dropdown-menu">
                          <li><a href="#!">Work Visa</a></li>
                          <li><a href="#!">Visit Visa</a></li>
                          <li><a href="#!">Multiple Visit Visa</a></li>
                        </ul>
                      </li>
                      <li><a href="#">Qatar</a></li>
                      <li><a href="#">Oman</a></li>
                    </ul>
                  </li>

                  <li class="nav-item dropdown">
                    <a
                      href="#"
                      class="nav-link dropdown-toggle"
                      data-toggle="dropdown"
                      >Man Power <i class="fa fa-angle-down"></i
                    ></a>
                    <ul class="dropdown-menu" role="menu">
                      <li><a href="#">Saudia Arab</a></li>
                      <li><a href="#">Oman</a></li>
                      <li><a href="#">kuwait</a></li>
                      <li><a href="#">Qatar</a></li>
                      <li><a href="#">UAE/Dubai</a></li>
                      <li><a href="#">Bahrain</a></li>
                      <li class="dropdown-submenu">
                        <a
                          href="#!"
                          class="dropdown-toggle"
                          data-toggle="dropdown"
                          >Parent Menu</a
                        >
                        <ul class="dropdown-menu">
                          <li><a href="#!">Child Menu 1</a></li>
                          <li><a href="#!">Child Menu 2</a></li>
                          <li><a href="#!">Child Menu 3</a></li>
                        </ul>
                      </li>
                    </ul>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Omrah</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Hajj</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                  </li>
                </ul>
              </div>
            </nav>
          </div>
          <!--/ Col end -->
        </div>
        <!--/ Row end -->

        <!-- <div class="nav-search">
          <span id="search"><i class="fa fa-search"></i></span>
        </div> -->
        <!-- Search end -->

        <div class="search-block" style="display: none">
          <label for="search-field" class="w-100 mb-0">
            <input
              type="text"
              class="form-control"
              id="search-field"
              placeholder="Type what you want and enter"
            />
          </label>
          <span class="search-close">&times;</span>
        </div>
        <!-- Site search end -->
      </div>
      <!--/ Container end -->
    </div>
  </div>
</template>
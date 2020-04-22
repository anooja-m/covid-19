<template>
<div>
<!--Navbar-->
<nav class="navbar navbar-expand-lg navbar-light white">

  <div class="container"> 

    <a class="navbar-brand" href="#">
      <img src="./assets/icon.jpeg" height="30" alt="mdb logo">
    </a>

    <!-- Collapse button -->
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#basicExampleNav"
            aria-controls="basicExampleNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <!-- Links -->
    <div class="collapse navbar-collapse" id="basicExampleNav">

      <!-- Left -->
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link waves-effect" href="https://mdbootstrap.com/docs/jquery/" target="_blank">World</a>
        </li>
        <li class="nav-item">
          <a class="nav-link waves-effect" href="https://mdbootstrap.com/docs/angular/" target="_blank">India</a>
        </li>
        <li class="nav-item">
          <a class="nav-link waves-effect" href="https://mdbootstrap.com/docs/react/" target="_blank">Business</a>
        </li>
        <li class="nav-item">
          <a class="nav-link waves-effect" href="https://mdbootstrap.com/docs/vue/" target="_blank">News</a>
        </li>
      </ul>

      <!-- Right -->
      <ul class="navbar-nav nav-flex-icons">
        <li class="nav-item">
          <a href="https://www.facebook.com/mdbootstrap" class="nav-link waves-effect" target="_blank">
            <i class="fab fa-facebook-f"></i>
          </a>
        </li> 
        <li class="nav-item">
          <a href="https://twitter.com/MDBootstrap" class="nav-link waves-effect" target="_blank">
            <i class="fab fa-twitter"></i>
          </a>
        </li>
        <li class="nav-item">
          <a href="https://github.com/mdbootstrap/bootstrap-material-design" class="nav-link waves-effect"
             target="_blank">
            <i class="fab fa-github"></i>
          </a>
        </li>
        <li class="nav-item">
          <a href="https://mdbootstrap.com/docs/jquery/newsletter/"
             class="nav-link border border-light rounded waves-effect mr-2" target="_blank">
            <i class="fas fa-envelope mr-1"></i>Newsletter
          </a>
        </li>
      </ul>

    </div>

  </div>

</nav>
<!--/.Navbar-->
  <div class="container my-5 py-5 z-depth-1">

 
    <!--Section: Content-->
    <section class="px-md-5 mx-md-5 dark-grey-text text-center text-lg-left">

      <!--Grid row-->
      <div class="row">

        <!--Grid column-->
        <div class="col-lg-6 mb-4 mb-lg-0 d-flex align-items-center justify-content-center">

          <img src="./assets/covid.jpg" class="img-fluid" alt="">

        </div>
        <!--Grid column-->

        <!--Grid column-->
        <div class="col-lg-6 mb-4 mb-lg-0">

          <h3 class="font-weight-bold">COVID-19 Latest Updates</h3>

          <p class="font-weight-bold">That's a very nice subheading</p>

          <p class="text-muted">Coronavirus world tracker: Total number of coronavirus cases in India has reached 18,985, and the global tally stands at 2,511,528. Stay with Fawzlabs News for Covid-19 corona LIVE updates</p>

          <a class="font-weight-bold" href="#" >Learn more<i class="fas fa-angle-right ml-2"></i></a>

        </div>
        <!--Grid column-->

      </div>
      <!--Grid row-->


    </section>
    <!--Section: Content-->


  </div>
    <div class="container my-5 py-5 z-depth-1">
 

    <!--Section: Content-->
    <section class="text-center px-md-5 mx-md-5 dark-grey-text">

      <!--Grid row-->
      <div class="row d-flex justify-content-center">

        <!--Grid column-->
        <div class="col-lg-7">
<div v-bind:key="index" v-for="(item,index) in coronaData">
        </div>
        </div>
        <!--Grid column-->

      </div>
      <!--Grid row-->
    </section>
    <!--Section: Content-->
  </div>
  <div class="container mt-5">


  <!--Section: Content-->
  <section>

  	<!-- Grid row -->
    <div class="row">
      
      <!-- Grid column -->
      <div class="col-lg-7 mb-4 align-self-center text-center text-lg-left">

        <h2 class="h2 mb-5">Introducing an app for Fawzlabs News</h2>
        <p class="text-muted mb-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit, error amet numquam iure provident voluptate esse quasi, veritatis totam voluptas nostrum quisquam eum porro a pariatur veniam. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit, error amet numquam iure provident voluptate esse quasi, veritatis totam voluptas nostrum.</p>

        <button type="button" class="btn btn-cyan waves-effect btn-md ml-lg-0"><i class="fab fa-apple fa-lg pr-1"></i> App Store</button>
				<button type="button" class="btn btn-cyan waves-effect btn-md"><i class="fab fa-google-play fa-lg pr-1"></i> Google Play</button>
        
      </div>
      <!-- Grid column -->
      
      <!-- Grid column -->
      <div class="col-lg-5 mb-4">

				<!-- Featured image -->
        <div class="view overlay">
          <img class="img-fluid mx-auto" src="https://mdbootstrap.com/img/illustrations/app-user-colour.svg" alt="Sample image">
          <a>
            <div class="mask rgba-white-slight"></div>
          </a>
        </div>

      </div>
      <!-- Grid column -->

    </div>
    <!-- Grid row -->

  </section>
  <!--Section: Content-->


</div>
  <!-- Footer -->
<footer class="page-footer font-small special-color-dark pt-4">
 
  <!-- Footer Elements -->
  <div class="container">

    <!--Grid row-->
    <div class="row">

      <!--Grid column-->
      <div class="col-md-6 mb-4">

        <!-- Form -->
        <form class="form-inline">
          <input class="form-control form-control-sm mr-3 w-75" type="text" placeholder="Search"
            aria-label="Search">
          <i class="fas fa-search" aria-hidden="true"></i>
        </form>
        <!-- Form -->

      </div>
      <!--Grid column-->

      <!--Grid column-->
      <div class="col-md-6 mb-4">

        <form class="input-group">
          <input type="text" class="form-control form-control-sm" placeholder="Your email"
            aria-label="Your email" aria-describedby="basic-addon2">
          <div class="input-group-append">
            <button class="btn btn-sm btn-outline-white my-0" type="button">Sign up</button>
          </div>
        </form>

      </div>
      <!--Grid column-->

    </div>
    <!--Grid row-->

  </div>
  <!-- Footer Elements -->

  <!-- Copyright -->
  <div class="footer-copyright text-center py-3">© 2020 Copyright:
    <a href="https://mdbootstrap.com/education/bootstrap/"> Fawzlabs pvt.Ltd</a>
  </div>
  <!-- Copyright -->

</footer>
<!-- Footer -->
</div>
</template>

<script>
export default {
  data(){
    return{
    coronaData:[]
    }
  },
  mounted(){
    this.getData()
  }
 ,methods:{getData(){
            let config = {
        headers: {
          "x-rapidapi-host": "coronavirus-monitor.p.rapidapi.com",
		"x-rapidapi-key": "J0Ro1CsdqumshmT7wG8r7qa4SIKjp1jqJHnjsntT9vFj2eaZzk"
        }
      }
      axios.get('https://coronavirus-monitor.p.rapidapi.com/coronavirus/affected.php',config).then(response=>{
          this.coronaData=response.data
      })
    },
}
};
</script>
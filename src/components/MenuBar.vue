<template>
  <div class="navbar bg-light">
    <div class = "container">

        <div class ="navbar-header">
            <a class="navbar-brand" href="#"> {{ company_name}} </a>
        </div>

        <ul class="nav navbar-nav navbar-right"> 
            <li> <a href="#"> <i class="fa fa-home"> Home</i> </a></li>
        </ul>

    </div>
  </div>

  
</template>

<script>
export default {
  name: 'MenuBar',
  props: {
    company_name: String
  }
}
</script>



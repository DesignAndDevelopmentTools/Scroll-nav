# Scroll-nav
> Scroll nav

> # 1. Just write code (HTML):
```s
   <nav class="navbar navbar-default navbar-fixed-top bg transition">
          .....
    </nav>
 
   <section style="height:1000px;"> </section>
```

> #  2. Just write code (CSS):
```s
<style type="text/css">
    .bg {
      background: white;
      width: 100%;
      opacity: 0.8;
    }
    .bg li a,.navbar-brand{
      padding: 30px 20px;
    }

    .show {
      opacity: 0.8;
      background: teal;
    }
    .show a{
      color:white!important;
    }
    .show a .active{
      color:white!important;
    }

    .transition {    
      -webkit-transition: all 0.8s ease-in-out;
      -moz-transition: all 0.8s ease-in-out;
      -o-transition: all 0.8s ease-in-out;
      transition: all 0.8s ease-in-out;
    }

  </style>
```

> # 3. Just write code (JavaScript):
```s
<script type="text/javascript">
  $(window).scroll(function() {
    if ($(window).scrollTop() > 100 ){
      $('.bg').addClass('show');
    } else {
      $('.bg').removeClass('show');
    };    
  });
  </script>
```

> # 4. Then view result in your Browser.

//# YoonDaHyun.github.io

<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
<style>
  div{
    width:50px;
    height:50px;
    background:green;
  }
</style>
    <script src="http://code.jquery.com/jquery-3.3.1.js"></script>
    <script>
      $(document).ready(function(){
        $("div").click(function(){
          $(this).animate({left:'+=60'},1000);
          $(this).animate({width:'+=60'},1000);
          $(this).animate({height:'+=60'},1000);
        });
      });
      </script>
  </head>
  <body>
    <div>
    </div>

  </body>
</html>

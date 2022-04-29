# php-Fucntion-
PHP Function 

<b>code explain</b>

index.php


      <?php
          include("function.php");
      ?>

      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>PHP Functions</title>
      </head>
      <body>

      <h1>Table</h1>
          <?php
          // the funnction is create in fuction.php file
              print_name();
          ?>


      </body>
      </html>

According to above code
<br>
in first 3 lines

      <?php
          include("function.php");
      ?>
      
include the fucntion.php file, because the fuctions is in the function.php<br>

          <?php
          // the funnction is create in fuction.php file
              print_name();
          ?>
          
so, above code part i call for the function named 'print_name()'. <br>
<br><br><br><br>


*************************



fucntion.php
<br>
            <?php
                function print_name(){
                    echo "JehanKandy";
                }
            ?>


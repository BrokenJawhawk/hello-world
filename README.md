# hello-world
<!DOCTYPE html>
<html>

    <?php
        // http://localhost/SingIndustry/{joed | jotham}/myfirst/index.php         
        $WebAuthor = "Jotham Lim Shu Ping and Joed Lim Shu Yi"
    ?>

    <head>
    
        <link rel="stylesheet" href="css/styles.css">
        <title><?php echo $WebAuthor ?> First Web Site</title>
    </head>
    
    <body class="backgroundrain">
    <div class="center">
        <h1 class="white">twins portfolio</h1>
        
        <button type="button" onclick="document.getElementById('time').innerHTML = Date()">click to diplay time</button>

        <p id='time' class="white"></p>

<h2 class="white">this page is to show our skill in programming and art</h2>
<br>
<table class="customers stuff">
        <tr>
            <th>css</th><th>and</th><th>html</th>
        </tr>
        <tr>
            <td class= "red">red color</td><td class="green">green color</td><td class="blue">blue color</td>
        </tr>
        <tr>
            <td class=""></td><td class="">hover over me</td><td class=""></td>
        </tr>
    </table>
<br>
<br>

<div>
    <div class="">
<button type="button" onclick="myfunction1()" class="">portflio</button>

<p id="first" class="white infobox"></p>

<script> 
 function myfunction1() {
     document.getElementById("first").innerHTML = "this portfolio was done by Joed and Jotham Lim.Joed did all the graphics and art and Jotham did all the HTML,CSS,Javascript etc."
 }
 </script>

<br>

<button type="button" onclick="myfunction2()">Jotham</button>

 <p id="second" class="white infobox"></p>

 <script> 
 function myfunction2() {
     document.getElementById("second").innerHTML = "Hi I'm Jotham.I am a 12 years old and I did the HTMl,CSS and Jvscript."
 }
</script> 

<br>
<button type="button" onclick="myfunction3()">Joed</button>

 <p id="third" class="white infobox"></p>

 <script> 
 function myfunction3() {
     document.getElementById("third").innerHTML = "Hi I'm Joed.I am 12 years old and i like to draw and animate."
 }
</script>
</div>
</div>


<br>
<br>
<br>
<div>
<h2 class="white">our art</h2>
<br>
<div class="sb"><img src="../globalimg/emotion_1.0.png"><img src="../globalimg/christmas_tree1.png">
<img src="../globalimg/puppet_mask_1.0.png"><img src="../globalimg/christmas_tree_1.0.png">
<img src="../globalimg/raf.png"><img src="../globalimg/eye-animation1.0.gif"><img src="../globalimg/dagger1.0.png">
<img src="../globalimg/unfinish_work_from_joed.png">
 </script>
</div>
</div>
<canvas id="canvas"></canvas>


</body>
    <footer> 
        <p class="footer-credit">Copyright <span id="CopyrightYear">Copyright Year 2022</span> <?php echo $WebAuthor ?></p>
    </footer>

    <script src="js/scripts.js"></script> 
    <script>window.onload = OnLoad();</script>
    </body>
</html>

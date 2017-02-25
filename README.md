<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>valueAsNumber可以轻送的设置和读取该元素中的数值</title>
    </head>
      <script type="text/javascript">
             function sum () {
                 var number1=document.getElementById("number1").valueAsNumber;
                 var number2=document.getElementById("number2").valueAsNumber;
                 document.getElementById("result").valueAsNumber=number1+number2;
             }
      </script>
    <body>
           <form action="">
               <input type="number" id="number1">+
                <input type="number" id="number2">=
                 <input type="number" id="result"  readonly="readonly">  <!-- readonly 只读 -->
                  <input type="button" value="计算"  onclick="sum();">+
           </form>
    </body>
</html>

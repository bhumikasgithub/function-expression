<!DOCTYPE html>
<html lang="eng">
    <head><title>function expression</title></head>
    <body>
        <h2>demo on function expression</h2>
        <script>
           let age =+prompt("enter ur age");
           let result;
    if(age<18)
           result=function(){alert("sorry, Ur not eligible for vote");};
    else
        result=function(){alert("hi,welcome for voting0");};
    document.write(result);
    result();
    </script>
    </body>
</html>

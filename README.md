# Part-3
<script>    
function myFunction()
{
    var num1, num2, num3, num4, num5, posCount, negCount, zeroCount;

    num1 = parseInt(document.form.fnum1.value);
    num2 = parseInt(document.form.fnum2.value);
    num3 = parseInt(document.form.fnum3.value);
    num4 = parseInt(document.form.fnum4.value);
    num5 = parseInt(document.form.fnum5.value);
    posCount = 0;
    negCount = 0;
    zeroCount = 0;

   // num1 if then statement    
   
    if (num1 > 0)
        {
            posCount++;
        }
    if (num1 < 0)
        {
            negCount++;
        }
     if (num1 == 0)
        {
            zeroCount++;
        }
    // num2 if then statement
   
    if (num2 > 0)
        {
            posCount++;
        }
    if (num2 < 0)
        {
            negCount++;
        }
     if (num2 == 0)
        {
            zeroCount++;
        }
    // num3 if then statement
   
    if (num3 > 0)
        {
            posCount++;
        }
    if (num3 < 0)
        {
            negCount++;
        }
     if (num3 == 0)
        {
            zeroCount++;
        }
        // num4 if then statement
   
    if (num4 > 0)
        {
            posCount++;
        }
    if (num4 < 0)
        {
            negCount++;
        }
     if (num4 == 0)
        {
            zeroCount++;
        }
   
    // num5 if then statement
   
    if (num5 > 0)
        {
            posCount++;
        }
    if (num5 < 0)
        {
            negCount++;
        }
     if (num5 == 0)
        {
            zeroCount++;
        }
   
    document.form.result1.value = "Number of Positive numbers: " + posCount  + "\n" + "Number of Negative numbers: " + negCount + "\n" + "Number of Zeros: " + zeroCount;
 
        }
   
 </script>
<form name="form">
  Input a value
  <input type="number" name="fnum1">
  Input a value
  <input type="number" name="fnum2">
  Input a value
  <input type="number" name="fnum3">
  <br>
  <br>
  Input a value
  <input type="number" name="fnum4">
  Input a value
  <input type="number" name="fnum5">
<input type="button" value="submit" onclick="myFunction()">
  <br>
  <br>
  <textarea type="text" id="result1" rows="10" cols="50"></textarea>
  <br>
</form>

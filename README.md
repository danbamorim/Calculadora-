<!DOCTYPE html>
<html lang="en">

<head>
    <title> Calculadora javascript- Projeto para praticar javascript </title>
</head>

<body>

    <form>
        <table border="0">
            <tr>
                <td> Calculadora Simples em javascript e HTML </td>
            </tr>
            <tr>  
            <td>val1<input type="text" name="val1" id='val1'></td>
            <td> 
                <select name= "sinal" id="sinal">
                    <option value ="+"></option>
                    <option value ="-"></option>
                    <option value ="*"></option>
                    <option value ="/"></option>
                </select>
            </td>
            <td>val2<input type="text" name="val2" id='val2'></td>
            <td> <input type="button" value="=" onclick="calcular();" name=""></td> 
            <td><input type="text" name="result" id='result'></td>
            </tr>
        </table>
    </form>
<script type="text/javascript"> 
    function calcular(){ 
    let val = (document.getElementById("val1").value); 
    let val2 = (document.getElementById("val2").value); 
    let sinal = (document.getElementById("sinal").value); 
    let result = (document.getElementById("result").value);
    
    if(sinal =="+") result.value = val1 + val2 ;
    if(sinal =="-") result.value = val1 - val2 ;
    if(sinal =="*") result.value = val1 * val2 ;
    if(sinal =="/") result.value = val1 / val2 ;

    } 

</script>
</body>

</html>
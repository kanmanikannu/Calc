# Ex.08 Design of a Standard Calculator
## Date:

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
#### Calc.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style1.css">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <script>
        function fn(e){
            if (e.innerHTML == '='){
                output.value = eval(output.value);
            }
            else if (e.id == 'back'){
                v=output.value;
                output.value = v.substring(0,v.length-1);
            }
            else if(e.innerHTML== 'C'){
                output.value='';
            }
            else{
                output.value += e.innerHTML;
            }
        }
    </script>
    <div class="content">
    
    <div class="row mx-auto text-center " style=" width: 24rem;background-image: url(bg\ image.jpg);">
        
            <div class=" mx-auto text-center text-white" style=" width: 24rem;">(Kanmani U 212221040070)</div>
        
        <div class="col-12 my-4" >
            <input  type="text" name="" id="output" style=" width: 100%;height: 50px; border-radius: 25px; background: none;color: white;text-align: right;">
        </div>    
    
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">(</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">)</div>
    <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)">C</div>
    <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)" id="back"><i class="bi bi-backspace"></i></div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">7</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">8</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">9</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">*</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">4</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">5</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">6</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">-</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">1</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">2</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">3</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">+</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">0</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">.</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">%</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">/</div>
    <div class="m-3 col-11 btn btn-warning rounded-4" onclick="fn(this)">=</div>
    </div>
    </div>
  
    </body>
   
   
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
```
#### style.css
```
h1{
   text-align: center;
}
.content{
   position: absolute;
   top: 50%;
   left: 50%;
   transform: translate(-50%,-50%);
   
   
}
```
## OUTPUT:
![Screenshot (26)](https://github.com/kanmanikannu/Calc/assets/114866367/7803b58c-3f55-47c0-938f-7d3046c4d0f6)

![Screenshot (27)](https://github.com/kanmanikannu/Calc/assets/114866367/e86f1ee8-4bea-4986-8478-054c67ec7a32)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.

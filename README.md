<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Combining CSS class and element selectors</title>
        <style>
            p {
                font-family: monospace;
            }
            
            #donut-header {
                font-family: "Garamond", "Palatino", serif;
            }
            
            .fact {
                border-top: 1px solid rgb(222, 222, 222);
                border-bottom: 1px solid rgb(222, 222, 222);
                padding-top: 6px;
                padding-bottom: 6px;
                
            }
            
            .warning {
                background-color: red;
                color: white;
            }
            
        </style>
    </head>
    <body>
        
        <h1 id="donut-header">Donut Nutrition Facts</h1>

        <p class=" warning">
            Warning: Eating too many donuts can be bad for your health. 
        </p>

        <p>A donut is a type of <strong class="warning">deep fried</strong> dough confectionery or dessert food. The doughnut is popular in many countries and prepared in various forms as a sweet snack that can be homemade or purchased in bakeries, supermarkets, food stalls, and franchised specialty outlets.</p>
        
        <p class="fact">
           Fact: Donut can also be spelled "doughnut."
        </p>
        
        <p>The two most common types are the <strong>toroidal ring doughnut</strong> and the <strong>filled doughnut</strong>—which is injected with fruit preserves, cream, custard, or other sweet fillings. A small spherical piece of dough may be cooked as a doughnut hole. Other shapes include rings, balls, and flattened spheres, as well as ear shapes, twists and other forms. Doughnut varieties are also divided into cake and risen type doughnuts.</p>
    <p class=fact> The only reason donuts taste good is because of their sugar</p>
    </body>
</html>

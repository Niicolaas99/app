<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product App</title>
    <link rel="stylesheet" href="https://bootswatch.com/5/litera/bootstrap.min.css">
</head>
<body>
    
    <nav class="navbar navbar-light bg-light">
       <a href="" class="navbar-brand"> 

        Product App
       </a>  
    </nav>
    <div class="container">

       <div id="App" class="row pt-5">
          <div class="col-md-4">
             <div class="card">
               <div class="card-header">
                   <h4>Añadir un producto</h4>
               </div>
                    <form id="product-form" class="card-body">
                     <div class="form-group">
                        <input type="text" id="name" placeholder="Product Name"
                        class="form-control">
                     </div>
                     <div class="form-group">
                        <input type="number" step="0.01" id="price"  placeholder="Product Price" class="form-control">
                     </div>
                     <div class="form-group">
                     <input type="number" id="year" value="" min="1900" max="2023" class="form-control" placeholder="Year Product"
                     class="form-control">
                    </div>
                    <input type="submit" value="Save" class="btn btn-primary btn-block">
                  </form>
             </div>
         </div>
         <div id="product-list" class="col-md-8"> </div>   
        </div>
    </div>
</div>
<script src="app.js"></script>
</body>
</html>

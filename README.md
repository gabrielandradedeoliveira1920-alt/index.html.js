<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    </head>
    <body>   

    <script>
       alert("estou no head")
        var x = 'valor1';
        let y = 'valor2';
        var x = 'valoe3';
        //a instrução abaixo não finciona
        //apresenta o erro identifier 'y' has already beem declared
        //let y ='valor4'

        let a =1;
        a=2;
        const b=1;
        //a instrução abaixo não funciona
        //apresenta o erro assignment to constant variable.
        //b=2;

        console.log("teste com var");
        for (var i = 0; i <5; i++) {
            console,log("dentro do for" +i);
        }
        console.log("fora do for"+i);
       
        console.log("teste com let");
        for (let j= 0; i <5; j ++) {
            console.log("dentro do for"+i);
        }
        //i is not delined
        //console.log("fora do for"+i);

        console.log("teste das funções");
        function exemplovar() {
            console.log("ex var" + w);//undelined
            for(var w =0;w <5;w++){
                console.log("ex var"+w);
            };
        }
            console.log("ex var"+w);//5
        
        exemplovar();

        function exemplolet() {
            //console.log("ex let"+m);//m is not defined
            for(let m = 0; m < 5; m++){
                console.log("ex let*+m");
            };
            //console.log("ex let"+m);//m is not defined
            };
            exenplolet();
        
    </script>
        comsole.log("<b>erro de portugues...</b>");
        </script>   
</body>
</html># index.html.js

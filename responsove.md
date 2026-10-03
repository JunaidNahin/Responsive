*FLEX Box*

```<style>
        .container{
            border: 2px solid black;
            display: flex;
            justify-content: flex-end;
            height: 150px;
            align-items: center;
            flex-direction: column;
        }
        .box{
            border: 1px dashed blue;
            height: 50px;
            width: 50px;
        }
    </style>
    
    <div class="container">
        <div class="box">Box-1</div>
        <div class="box">Box-2</div>
        <div class="box">Box-3</div>
    </div>```

    1.display:flex will merge multiple rows into a single row
    2.justify-content work within the row
    3.align-items work within the column

    ```<style>
    .container{
    display:flex
    flex-wrap: wrap;
    }
    </style>
    
    <div class="container">
        <div class="box">Box-1</div>
        <div class="box">Box-2</div>
        <div class="box">Box-3</div>
    </div>``` 
    4.flex-wrap:wrap will divide the row into multiple row if it is difficult to manage all the elements into a single row 

    ```<style>
      .contaoner{
         display:flex;
         justify-content: flex-end *it will take the elements at the last of the row*
         flex-direction: column; *it will turn the direction of the contents stowards the column *
      }
    </style>
    
    <div class="container">
        <div class="box">Box-1</div>
        <div class="box">Box-2</div>
        <div class="box">Box-3</div>
    </div>```

    1.```**More about justify content:**
                justify-content:flex-start *it will start the content from the begining of the row*
                justify-content:center *The content will be in the middle of the row*
                justify-content:space-between *it will create space in between the elements*
                justify-content:space-around *It will give less space at the begining and at the end of the content but more space will be given in the between of the contents*
                justify-content:space-evenly *it will give equal gap from the start to the end of the content*```

    2.align-items: all the properties of justify-content and align-items are simillar but align-items will work column wise
    
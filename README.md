# layout-
    <!DOCTYPE html>
    <html lang="en">
    <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <meta http-equiv="X-UA-Compatible" content="ie=edge">
         <title>Document</title>
         <style>
             *{
                padding: 0;
                margin: 0;
             }
             body>div{
               margin-top: 30px;
             }
             .fleat{
               overflow: hidden;
             }
             .fleat div{
               min-height: 100px;
               height: 100%;
             }
             .fleat .left{
               float: left;
               width: 300px;
               background-color: red;
             }
             .fleat .center{
               background-color: yellow;
               overflow: hidden;
             }
             .fleat .right{
                float: right;
                width: 300px; 
                background-color: blue;
             }
             .postion{
                position: relative;
                min-height: 100px;
             }
             .postion div{
                position: absolute;
                height: 100%;
             }
            .postion .left{
               width: 300px;
               left: 0;
               background-color: red;
             }
             .postion .center{
             left: 300px;
             right: 300px;
             background-color: yellow;
         }
         .postion .right{
             width: 300px;
             right: 0;
             background-color: blue;
         }
         .flex{
           display: flex;
         }
         .flex div{
             min-height: 100px;
         }
         .flex .left{
             width: 300px;
             background-color: red;
         }
         .flex .center{
             flex: 1;
             background-color: yellow;
         }
         .flex .right{
             width: 300px;
             background-color: blue;
         }
         .table{
           display: table;
           width: 100%;
         }
         .table div{
             min-height: 100px;
         }
         .table .left{
             display: table-cell;
             width: 300px;
             background-color: red;
         }
         .table .center{
             display: table-cell;
             background-color: yellow;
         }
         .table .right{
             display: table-cell;
             width: 300px;
             background-color: blue;
         }
         .grid{
           display: grid;
           width: 100%;
           grid-template-rows: 100px;
           grid-template-columns: 300px auto 300px;
         }
         .grid .left{
             background-color: red;
         }
         .grid .center{
             background-color: yellow;
         }
         .grid .right{
             background-color: blue;
         }
         /* 每个方案的优缺点 */、
             /*浮动 清除浮动 他会脱离文档流 清除浮动和周边的元素处理的比较好的话 他的兼容性比较好 */
             /* absolute  快捷 不容易出问题 整个元素脱离文档流，后面的元素会向上，可使用性比较差*/
             /* flex 比较完美的，手机端经常用 */
             /* table 兼容性比较好，但是如果某个元素需要增高时 其他元素都会增高 */
             /* grid  这是新的技术  */
         /* 把高度去掉 */
             /* 只有flex 和 table 能用 其他都不能用了 */
         /* 他们的兼容性 那个最实用的 */
         /*  页面布局小节 
             1.语义化掌握到位
             2.页面布局理解深刻
             3.css基础知识扎实
             4.思维灵活且积极上进
             5.代码书写规范
         */

     </style>
     </head>
     <body>
        <div class="fleat">
           <div class="left"></div>
           <div class="right">
           </div>
           <div class="center">
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
           </div>
        </div>
        <div class="postion">
           <div class="left"></div>
           <div class="center">
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
           </div>
           <div class="right"></div>
        </div>
        <div class="flex">
           <div class="left"></div>
           <div class="center">
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
           </div>
           <div class="right"></div>
       </div>
       <div class="table">
         <div class="left"></div>
         <div class="center">
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
         </div>
         <div class="right"></div>
       </div>
       <div class="grid">
             <div class="left"></div>
             <div class="center">
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
                 <p>增加高度</p>
             </div>
             <div class="right"></div>
     </div>
    </body>
    </html>

# CSS基础
CSS 的全称是 Cascading Style Sheet（层叠样式表），它主要用来控制网页的样式。

我们通过修改h2元素的style属性的color值来改变文本颜色。<h2 style="color: blue;">CatPhotoApp</h2>最好以;结束syle 
修改时直接在h2修改
用class选择器设置多个元素的样式：<style>
                                .red-text;     （注意.
                                 {color=red;}
                                 </style>
                                 然后只需要在后面需要更改颜色的文本头添加：class="red-text"就能全改成红色
                                 <h class="red-text">
                                 <p class="red-text">![image](https://user-images.githubusercontent.com/91460930/135033270-debc6747-94d3-4fbc-9757-eb18cf380189.png)

                                   
字体修改:
                                   font-size属性修改字体大小
                                   font-family修改字体样式
                                   p{font-family:Lobster;}
                                   
      *引入谷歌字体：首先需要复制google字体的url，然后选需要引入的字体（类似复选框
                                  
<link href="网址"/.css?  family="Lobster" rel="" type=""(这俩暂时不知道干啥的>
                                   
                                   字体降级：字体不可用时用下一种
                                   p{font-family= Lobster,monospace;}当Lobster不可用时就用monospace
                                   注意：当引入的字体中含有空格时需要用""括起来，注释:<!-- 内容..........-->
                            
2021/9/29 0:50 一天就学了这点，啊啊啊
                                   2021/9/30 上午写的忘记保存了。都是很简单的内容，总结一下
                                   ：调整图片大小：.属性名{
                                                            width:(后面可用像素px也可用百分比%
                                   
                                   边框颜色：.属性名{
                                                        border-color:   ;(颜色
                                                        border-style:solid;
                                                         border-width:  ; (厚度
                                                        border-radius:   ;(圆角边框50%时候是个园
                                   
                                   背景色：.{
                                      
                                                background-color:   ;
                                   
                                   同一个元素添加多个属性值<p class="background-color border-color">只需要中间空格
  
                                    设置元素ID：<h2 id="123">
  
                                    id属性：不可重用，只能应用于一个元素，id优先级高于class，同时应用时会优先用id
  
                                    目前来看#id{background-color：green;}作用与.属性{background-color;}一样，引用时一个是id=""，另一个是class=""\
  
  

  
  
  新内容：调整元素内边距：每个HTML元素周围的矩形空间由三个属性决定padding(内边距），margin(外边距），border（边框）
          padding控制元素内容与border之间空间大小![image](https://user-images.githubusercontent.com/91460930/135563286-f97830fc-5a86-4244-948d-110d1bdb97e5.png)
此外还有padding-top.padding-bottom,padding-right ,padding-left.决定与各个方向的内边距(color:#fff是白色等于white）
          padding:10px 20px 10px 20px;按照上右下左的顺时针方向设定，这样就不必每次写那么多,margin也是同理
  
  
  
  
  
          margin：控制元素与周围其他元素的距离大小。如果margin值为负，就会变成与外边框的距离且元素变得更大，值为正就是与内边框的距离![image](https://user-images.githubusercontent.com/91460930/135563476-7e93f799-7e80-4336-8dbe-f6fcb36b1359.png)上下左右都会变
  此外margin也有上下左右四个方位
  
  
  
  
  如果不设定padding 的值，默认为0.内边距padding决定边框的大小，margin上下值不会改变边框大小，左右值改变会改变左右边框长短
  
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }
  
  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }
  
  <h5 class="injected-text">margin</h5>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box blue-box">padding</h5>
</div>(text-align:center;作用是中间对齐）
  
  使用属性选择器修改元素样式：[type='checkbox']{magrgin 10px 0px 15px 0px ;}


                                  
  
  
  
  
    
  
  

    
  
  

                                   

       
                                   
                                   
                             
                                    
                                    
                                    
                                    
                                    
                                    
                                    
                                   
                                    
            

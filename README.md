# css-triangle
纯css写三角形
原理如下

    		.main {
    		    width: 0;
    		    height: 0;
    		    border-left: 100px solid blue;
    		    border-right: 100px solid green;
    		    border-bottom: 100px solid red;
    		    border-top: 100px solid yellow;
    		}
    		
<br>
<img src="https://dongeg.github.io/public-images/css-triangle/832C.tmp.jpg" />
<br />
宽高为0，边框自成三角形，所以css写三角形，尖朝那边，就让它无对边边框，临便边框透明

如尖朝上的三角形

        #triangle-up {
            width: 0;
            height: 0;
            border-left: 50px solid transparent;
            border-right: 50px solid transparent;
            border-bottom: 100px solid red;
        }

<img  src="http://files.jb51.net/file_images/article/201310/201310290941121.jpg?201392994443" />




朝下


        #triangle-down {
            width: 0;
            height: 0;
            border-left: 50px solid transparent;
            border-right: 50px solid transparent;
            border-top: 100px solid red;
        }
        
朝左

        #triangle-left {
            width: 0;
            height: 0;
            border-top: 50px solid transparent;
            border-right: 100px solid red;
            border-bottom: 50px solid transparent;
        }

朝右


        #triangle-right {
            width: 0;
            height: 0;
            border-top: 50px solid transparent;
            border-left: 100px solid red;
            border-bottom: 50px solid transparent;
        }
        
        
        
 左上
    
            #triangle-top-left {
              width: 0;
              height: 0;
              border-top: 100px solid red;
              border-right: 100px solid transparent;
          }




右上

        #triangle-topright {
            width: 0;
            height: 0;
            border-top: 100px solid red;
            border-left: 100px solid transparent; 
        }
        
        
        
左下        
        
        #triangle-bottomleft {
            width: 0;
            height: 0;
            border-bottom: 100px solid red;
            border-right: 100px solid transparent;
        }
        
        
        
        
右下        
        
        #triangle-bottomright {
            width: 0;
            height: 0;
            border-bottom: 100px solid red;
            border-left: 100px solid transparent;
        }

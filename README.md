# code-template/*

            「 strike my soul 」
     
  TEMPLATE CRIADO POR ROSS, NÃO TIRE OS CRÉDITOS
          
*/

#rstrikemysoul {
  width: 575px;
}

#rstrikemysoul .rcontainer {
    width: 100%;
    background: #fff;
    border: 1px solid #e8e8e8;
    padding: 50px 20px;
    outline: 10px solid #fff;
    margin: 10px 0;
}

#rstrikemysoul .rtitle {
  width: 285px;
  display: inline-block;
  vertical-align: top;
  margin-top: 13px;
  margin-right: 20px;
  font: 900 30px/30px Playfair Display;
  text-transform: uppercase;
  color: #aaa;
}

#rstrikemysoul .rimg {
  width: 60px;
  height: 60px;
  background: center/cover;
  background-blend-mode: multiply;
  border-radius: 100%;
  display: inline-block;
  margin: 0 5px;
  opacity: .9;
  -moz-transition: all .3s ease-in-out; 
  -webkit-transition: all .3s ease-in-out; 
  ms-transition: all .3s ease-in-out; 
  -o-transition: all .3s ease-in-out;
}

#rstrikemysoul .rimg:hover {
  filter: grayscale(1);
  transform: rotate(-10deg);
  -moz-transition: all .3s ease-in-out; 
  -webkit-transition: all .3s ease-in-out; 
  ms-transition: all .3s ease-in-out; 
  -o-transition: all .3s ease-in-out;
}

#rstrikemysoul .rtexto {
  margin-top: 40px;
  padding: 10px 25px;
  font: 13px/22px Roboto;
  text-align: justify;
  color: #000;
}

#rstrikemysoul:after {
  content: "「R」";
  font: bold 8px/12px Consolas;
  color: #8e8e8e;
  text-transform: uppercase;
  letter-spacing: -.5px;
  opacity: .6;
}

#rstrikemysoul:hover::after {
  content: "「ROSS @ FÊNIX GRAPHIC」";
}

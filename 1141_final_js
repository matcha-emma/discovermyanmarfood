function changeword()
{
   var now = new Date(); // 獲取現在日期時間
   n_sec = now.getSeconds(); //獲得當前秒數
   css_pre = "<span id='ptext' class='button_text'>"; //設定HTML語法
   css_post = "</span>";  
   if (n_sec % 2 != 0) { //每1秒換一次
      d=document.getElementById("ptext").innerHTML=css_pre+"企 畫 書"+css_post;
   } //找網頁中 ptext id 名稱
   else {
      d=document.getElementById("ptext").innerHTML=css_pre+"Proposal"+css_post;
   }
   window.setTimeout("changeword()",1000); //每一秒鐘執行一次程式本身
}
changeword();


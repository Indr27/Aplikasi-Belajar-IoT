Splash Padlock
ion-view.padlock-view ion-content {
	 background-color: #fff !important;
  	 border-radius: 40px 40px 0 0 !important; 
}

ion-view.padlock-view .card {
  	box-shadow: none;
}


ion-view.padlock-view div.item.item-text-wrap.item-custom:first-child {
  	visibility: hidden;	
}

ion-view.padlock-view div.item.item-text-wrap.item-custom:first-child:before {
  	content: "Selamat Datang";
  	color: #000;
  	text-align: center;
  	width: 100%;
  	display: block;
  	visibility: visible; 	
  	font-weight: bold;
  	font-size:	18px;
  	
}

ion-view.padlock-view .item.item-body.item-custom.text-center {
  	background-image: url("https://alicestech.com/wp-content/uploads/2020/10/image-2.png");
  	background-color: transparent;
  	background-repeat: no-repeat;
  	background-size: 45%;
    Background-position: center; 
  	height: 225px;
}

ion-view.padlock-view .item.item-body.item-custom.text-center {
	font-size: 0;
  	hight: 150px;
  	padding: 0 !important;
}	  	

ion-view.padlock-view [ng-click="padlockLogin()"] {
 	visibility: hidden;
}

ion-view.padlock-view [ng-click="padlockLogin()"]:after {
 	visibility: visible;
  	content: "Masuk";
  	text-align: center;
  	display: block;
  	widght: 60%;
  	margin: 0 10%;
  	font-weught: bold;
  	font-size: 18px;
  	background-color: #00A4A4;
  	color: #fff;
    border-radius: 30x !important;  	
	padding: 10px 15px;
}

ion-view.padlock-view .item.item-icon-left.item-custom.ng-binding {
	padding: 0 !important;
  	
}

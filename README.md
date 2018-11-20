# BottomView
 	bottomView.setTextColors(Color.BLACK)//设置未选中标题颜色
                .setOpen(true)//是否显示中间大按钮，当标题个数为奇数是，自动不显示按钮
                .setTextCheckColor(Color.BLUE)//设置选中标题颜色
                .setSquare(true)//设置按钮是否居中还是往上突起，当setOpen(false)此设置无效
                .setImageCheck(imagesList)//设置选中时图片
                .setMiddleImage(R.mipmap.difennaa)//设置中间大按钮的图片
                .setImagesWidthHeight(150, 150)//设置中间大按钮的高宽度
                .setImageBottom(40)//设置大按钮的下边距
                .setNameOrImage(nameList, imageList)//设置每个item的标题和图片
                .setImageWidthHeight(70, 70)//设置item图片的高宽度
                .init();//初始化
        bottomView.setOnClick(this);//点击回调
        bottomView.setPosition(0);//设置选中的item
	

<img src="https://github.com/PaiDaXinA/img-folder/blob/master/S81120-13441435.jpg" with="375" height="800" floate="left">
<img src="https://github.com/PaiDaXinA/img-folder/blob/master/S81120-13451101.jpg" with="375" height="800" floate="left">
<img src="https://github.com/PaiDaXinA/img-folder/blob/master/S81120-13455391.jpg" with="375" height="800" floate="left">
	
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Add the dependency
  
  	dependencies {
	        implementation 'com.github.PaiDaXinA:BottomView:Tag'
	}

##FengHuangNew

<<<<<<< HEAD
仿凤凰新闻app---第十周学习Android路上
最重要的事情放前面说，请用wifi测试,最好也下载凤凰新闻app对比。
若运行app报空指针，可能接口返回的数据结构有所变化。
=======
浠垮嚖鍑版柊闂籥pp---绗崄鍛ㄥ涔燗ndroid璺笂
鏈�閲嶈鐨勪簨鎯呮斁鍓嶉潰璇达紝璇风敤wifi娴嬭瘯,鏈�濂戒篃涓嬭浇鍑ゅ嚢鏂伴椈app瀵规瘮銆�
鑻ヨ繍琛宎pp鎶ョ┖鎸囬拡锛屽彲鑳芥帴鍙ｈ繑鍥炵殑鏁版嵁缁撴瀯鏈夋墍鍙樺寲銆�
>>>>>>> origin/master

---
鍏充簬浣滆�咃細
RealMoMo
<<<<<<< HEAD
> 关于我，欢迎关注  
   微信：[Real_Mo]()  
   邮箱：momo_weiye@126.com
=======
> 鍏充簬鎴戯紝娆㈣繋鍏虫敞  
   寰俊锛歔Real_Mo]()  
   閭锛歮omo_weiye@126.com
>>>>>>> origin/master
-------------
####寮�鍙戠洰鐨�: 
<br>1.缁冩墜</br>
<br>2.鐔熸倝鎶撳寘</br>

###棰勮鐣岄潰

<br>涓嶅姩鎬佸氨涓嶆斁浜嗭紝鏈夐渶瑕佸彲浠ョ洿鎺ヤ笅杞組yApk瀹夎杩愯銆�</br>


<br>鏂伴椈鐣岄潰</br>
	<br> ![image](https://github.com/RealMoMo/FengHuangNews/blob/master/pic/pic1.png)</br>

<br> 鐩存挱鐣岄潰</br>
 <br> ![image](https://github.com/RealMoMo/FengHuangNews/blob/master/pic/pic2.png)</br>

<br> 鎼滅储鐣岄潰</br>
  <br> ![image](https://github.com/RealMoMo/FengHuangNews/blob/master/pic/pic3.png)</br>

<br> 瑙嗛鐣岄潰</br>
  <br>  ![image](https://github.com/RealMoMo/FengHuangNews/blob/master/pic/pic4.png)</br>

<br>  鍙戠幇鐣岄潰</br>
   <br>  ![image](https://github.com/RealMoMo/FengHuangNews/blob/master/pic/pic5.png)</br>

     
   

###寮�鍙戠幆澧�
Android Studio2.0


### 涓嬭浇瀹夎
瀵煎叆椤圭洰锛岄噸鏂伴厤缃�傚悎浣犲紑鍙戠幆澧僢uild.gradle鏂囦欢
瀵煎叆閲岄潰app妯″潡锛岄噸鏂伴厤缃�傚悎浣犲紑鍙戠幆澧僢uild.gradle鏂囦欢
娉ㄦ剰锛歫ava-->momo鍖呬笅鎵嶆槸涓昏浠ｇ爜锛屽叾浠栨槸绗笁鏂圭櫥褰曞杩涙潵鐨勫寘銆�

```java  
  
apply plugin: 'com.android.application'

android {
    compileSdkVersion 23
    buildToolsVersion "23.0.3"

    defaultConfig {
        applicationId "momo.com.week10_project"
        minSdkVersion 16
        targetSdkVersion 23
        versionCode 1
        versionName "1.0"
    }
    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android.txt'), 'proguard-rules.pro'
        }
    }
}

dependencies {
    compile fileTree(dir: 'libs', include: ['*.jar'])
    testCompile 'junit:junit:4.12'
    compile 'com.android.support:appcompat-v7:23.4.0'
    compile 'com.squareup.retrofit2:retrofit:2.1.0'
    compile 'com.squareup.retrofit2:converter-gson:2.1.0'
    compile 'com.squareup.retrofit2:converter-scalars:2.1.0'
    compile 'com.android.support:design:23.4.0'
    compile 'in.srain.cube:ultra-ptr:1.0.11'
    compile 'com.youth.banner:banner:1.4.4'
    compile 'com.github.bumptech.glide:glide:3.7.0'
    compile files('libs/MobCommons-2016.1107.1809.jar')
    compile files('libs/MobTools-2016.1107.1809.jar')
    compile files('libs/ShareSDK-Core-2.7.10.jar')
    compile files('libs/ShareSDK-QQ-2.7.10.jar')
    compile files('libs/ShareSDK-QZone-2.7.10.jar')
    compile files('libs/ShareSDK-SinaWeibo-2.7.10.jar')
    compile files('libs/ShareSDK-TencentWeibo-2.7.10.jar')
    compile files('libs/ShareSDK-Wechat-2.7.10.jar')
    compile files('libs/ShareSDK-Wechat-Core-2.7.10.jar')
    compile files('libs/ShareSDK-Wechat-Favorite-2.7.10.jar')
    compile files('libs/ShareSDK-Wechat-Moments-2.7.10.jar')
}

  
```

###Thanks
Everyone who has contributed code and reported issues and pull requests!



###TODO
 * 1.鏈琣pp娌℃湁鍋氱紦瀛樺姛鑳姐��
 * 2.鎵�鏈塴istview鐐瑰嚮item锛屾病鏈夊啓甯冨眬灞曠ず鍐呭锛岄兘鏄敤webview灞曠ず鐨勩��
 * 3.鐩存挱鍐呭鐨勮棰戞帴鍙ｏ紝娌℃湁鎶撳埌銆傛眰濂藉績浜鸿兘鎻愪緵涓嬨��
 * 4.鏂伴椈鐣岄潰鍙啓浜嗕袱涓ā鍧�--澶存潯鍜屼綋鑲层�傚叾浠栨ā鍧楁�濊矾閮芥槸涓�鑷淬�傦紙鎳傚氨鍙互浜� ^_^锛�
 * 5.瑙嗛娌℃湁瀹炵幇鐐瑰嚮杩涘幓鎾斁鐨勫姛鑳姐�傛噦鍦╨istview鎾斁瑙嗛锛屼及璁＄偣鍑昏繘鍘绘挱鏀鹃兘鏄皬浜嬨��
 * 6.鍙戠幇妯″潡鐨勬病鏈夊疄鐜發istview item鐐瑰嚮鍔熻兘锛屾帴鍙ｈ繑鍥炵殑鏁版嵁锛岄兘涓嶈兘鐢╓ebView灞曠ず銆傞渶瑕佽嚜宸辫В鏋愬唴瀹癸紝鍐欏竷灞�杩涜灞曠ず銆�
 * 7.鎴戠殑妯″潡鍙啓鐢╩ob绗笁鏂圭殑鐧诲綍銆�
 * 8.鍚勬ā鍧楃殑listview锛岄兘娌℃湁鍐欎粈涔堝弻鍑诲ご閮ㄥ洖鍒伴《閮ㄧ殑鍔熻兘銆傦紙鎳掑緱鍐�
 * 9.鏂伴椈妯″潡娣诲姞item 榛樿娣诲姞RealMo鐨刬tem,瀹炵幇鍔熻兘鐨勬牱瀛愯�屽凡銆�
 * 10.webview鐨勯噸瀹氬悜鐨勬柟娉曪紝鎴戞病鏈夐噸鍐欍�傝嫢璺宠浆鑷繁鎵嬫満娴忚鍣紝鑷繁閲嶅啓璇ユ柟娉曞嵆鍙��
 * 11.璇pp娌℃�庝箞鑰冭檻鎬ц兘浼樺寲闂銆�
 * 12.widget鍖呬笅鐨刬conview nameview鍏�4涓嚜瀹氫箟锛屾垜娓ｅ簲璇ョ敤涓�涓娊璞＄被鐩存帴寮勫ソ灏辫銆�   锛堟噿路路路蹇冨路路路锛�
 * 13.瑙嗛鎾斁鐣岄潰涓嶅お鍙嬪ソ銆�
 * 14.鑻ョ洿鎺ョ敤android studio瀹夎apk,weibo涓嶈兘绗笁鏂瑰疄鐜颁笉浜嗙櫥褰曘�傝鑷繁鏀筧ssets鏂囦欢澶圭殑ShareSDK鐨勯厤缃�

###Version
<br>1.0瀹炵幇澶ц嚧鍔熻兘----2016.12.16</br>
<br>1.1瀹屽杽娉ㄩ噴銆佺簿绠�浠ｇ爜----2016.12.17</br>

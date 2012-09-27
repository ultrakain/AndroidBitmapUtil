AndroidBitmapUtil
=================

Android Bitmap Object To .bmp image file

Usage
=================
<pre><code>
String sdcardBmpPath = Environment.getExternalStorageDirectory().getAbsolutePath() + "/sample_text.bmp";
Bitmap testBitmap = BitmapFactory.decodeResource(getResources(), R.drawable.sample_text);
AndroidBmpUtil bmpUtil = new AndroidBmpUtil();
boolean isSaveResult = bmpUtil.save(testBitmap, sdcardBmpPath);
</code></pre>


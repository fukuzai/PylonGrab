# PylonGrab
https://github.com/fukuzai/PylonGrab

# 概要
pylon APIを用いた撮像

/*
   This sample illustrates how to grab images and process images asynchronously.
   This means that while the application is processing a buffer,
   the acquisition of the next buffer is done in parallel.
   The sample uses a pool of buffers. The buffers are automatically allocated. Once a buffer is filled
   and ready for processing, the buffer is retrieved from the stream grabber as part of a grab
   result. The grab result is processed and the buffer is passed back to the stream grabber by
   disposing the grab result. The buffer is reused and refilled.
   A buffer retrieved from the stream grabber as a grab result is not overwritten in the background
   as long as the grab result is not disposed.
*/


以下にサンプルプログラムあり
C:\Program Files\Basler\pylon 5\Development\Samples\C#\Basler.Pylon\Grab

# 環境
<ul>
  <li>Windows10 64bit</li>
  <li>Pylon 5.1.XXXX</li>
  <li>Visual Stuio 2015 pro (C#)</li>
  <li>カメラ：raL4096-24gm</li>
</ul>

# screenshot
入力画像<br>
![screenshot](https://github.com/fukuzai/PylonGrab/blob/master/screenshot1.png)

![screenshot](https://github.com/fukuzai/PylonGrab/blob/master/screenshot2.png)

# 改定履歴

<ul>
  <li>2020-12-01 初版。</li>
  
</ul>

# 備考


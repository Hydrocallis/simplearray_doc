.. SimpleArray documentation master file, created by
   sphinx-quickstart on Wed Nov 16 14:30:57 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Adjustment of maximum number of vertices
========================================
最大頂点数の調整

|image|

思わぬ動作で、ブレンダーの限界を超えた頂点数アレイ配列を入力する事があります。
防止機能で設定以上の頂点数になったら動作を停止して確認をする機能を追加しました。

An unexpected operation may cause the input of an array array of vertices that exceeds the blender's limit.
A function has been added to stop the operation and check if the number of vertices exceeds the setting in the prevention function.
最大頂点数の警告表示の調整機能を
アドオンのプレファレンスに追加。

Added the ability to adjust the maximum vertex warning display,
Added to add-on preferences


事前確認画面

Pre-confirmation screen

|11|

設定をリセットしたい場合はプリセットで「デフォルト」を選択して下さい。

If you want to reset the settings, select "Default" in Presets.
|12|

.. #############################ここから引用用の画像集#############################


.. |image| image:: /img/10_maxhold.jpg
   :scale: 100%

.. |11| image:: /img/11_maxhold.jpg
   :scale: 100%

.. |12| image:: /img/11_maxhold.jpg
   :scale: 100%









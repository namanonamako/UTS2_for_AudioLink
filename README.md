# UTS2_for_AudioLink
 llealloo氏のVRChatギミックである[vrc-udon-audio-link](https://github.com/llealloo/vrc-udon-audio-link/)に対応したUTS2シェーダーです。  
 AudioLinkシステムが導入されたワールドであれば、音楽に合わせてアバターのエミッションが動作するようになります。  
 
  **注意**   
  AudioLinkはバージョン2にのみ対応しています。  
  バージョン1が設置されたワールドでは動作しません。  
 
# デモ
 <img src="https://raw.githubusercontent.com/wiki/namanonamako/UTS2_for_AudioLink/images/Demo.gif" width=50%>  
アバターの服にワールド音源に反応するインジケーターを表示しています。  

# 要件
 アバターに利用する際は本unitypackageのみで利用可能です。  
 
 unity上で動作確認をする場合は以下が必要です。
* VRCSDK3-AVATAR- 
* vrc-udon-audio-link  
 
 VRChat内で動作させるにはvrc-udon-audio-linkが導入されているワールドにいる必要があります。  
 デモワールドは上記AudioLinkのリポジトリにリンクがあります。  
 
# インストール
* アバターへの導入  
 本Unitypackageをプロジェクトにインポートしてください。  
 シェーダーは以下の階層にあります。  
 UnityChanToonShader/Namako/AudioLink/*    
 
* アバターの動作確認  
 VRCSDK・AudioLinkを導入後、AudioLink/AudioLinkAvatarをシーンに配置。  
 AudioLinkAvatar/AudioLinkInputに任意の音楽ファイルを設定しシーンを再生してください。  
 音は聞こえないくらい小さくなります。  

# Author
  
* 作成者：namanonamako  
* twitter：[@Iiron_lung](https://twitter.com/Iiron_Lung)  
 
# License
 [UTS2](https://github.com/unity3d-jp/UnityChanToonShaderVer2_Project)に準拠します  

---
layout: default
---


# ShaderとModularAvaterに関して
* 現在**lilToon**に対応している衣装は**サバンナストリート レイシャークコーデ**のみです.
* 他のアバター対応衣装は**順次,ArktoonShaderからlilToonに変更&ModularAvater対応**していきます.
  
---

# 注意
* ReadMe,Shader等は"OtherData.zip"に含まれています*

* マテリアルエラーになる場合は"OtherData.zip"に同梱しているシェーダーをインポートして下さい *

* こちらは衣装のみです.アバターは含まれません. *

* 水着は含まれません. *

* 水着等を着せる際は各Shape Keyにて調整して下さい. *

* 動画の衣装は制作当初のものなので若干異なります. *

---

# 対応モデル
## LilToon & ModularAvater
### サバンナストリート レイシャークコーデ ( イリオ1.1 )( SVST02 )
CasualAndCoolJacket_SVST02_X.x.unitypackageに入っています
- [ サバンナストリート レイシャークコーデ ]( https://avatarchan.booth.pm/items/3964062 )

## ArktoonShader
### 白星アバター
CasualAndCoolJacket_CustaChan_X.x.unitypackageに入っています
- [ レムリカ ]( https://hakusei-avatar.booth.pm/items/1323709 )
- [ ロゼリッタ ]( https://hakusei-avatar.booth.pm/items/3186170 )
- [ メディシアス ]( https://hakusei-avatar.booth.pm/items/1995172 )
- [ 白神鈴 ]( https://hakusei-avatar.booth.pm/items/1323719 )
- [ えるるちゃん ]( https://hakusei-avatar.booth.pm/items/2486319 )
- [ かすたちゃん ]( https://hakusei-avatar.booth.pm/items/1795010 )
- [ 明明（ミンミン） ]( https://hakusei-avatar.booth.pm/items/3695081 )

### こまどアバター
CasualAndCoolJacket_Rusk_X.x.unitypackageに入っています
- あまなつ (販売終了アバター)
- ラムネ Re (販売終了アバター)
- [ ミント ]( https://komado.booth.pm/items/2258111 )
- [ ミルク Re ]( https://komado.booth.pm/items/2953391 )
- [ ラスク ]( https://booth.pm/ja/items/2559783 )
- [ カリン ]( https://komado.booth.pm/items/3470989 )

### ミーシェ
CasualAndCoolJacket_Mishe_X.x.unitypackageに入っています
- [ ミーシェ ]( https://booth.pm/ja/items/1256087 )

### サバンナストリート ワイルドキャットコーデ ( イリオ1.0 ) ( SVST01 )
CasualAndCoolJacket_SVST01_X.x.unitypackageに入っています
- [ サバンナストリート ワイルドキャットコーデ ]( https://avatarchan.booth.pm/items/3188683 )

---

# 着せ替えツール (ModularAvater対応衣装の場合)
ModularAvater対応版衣装はModularAvaterをご利用ください.
対応したアバター直下にセットアップされたPrefabをD&Dするだけで着せ替え,専用ExpressionMenuの追加が可能になります.

# 着せ替え用おすすめツール (ModularAvater未対応版,ModularAvaterを使用しない場合)
 - [ Auto Dresser(有料) ]( https://booth.pm/ja/items/1300847 )

 - [ 白星アバター向け着せ替え衣装の導入方法（AutoDresser版）] ( https://note.com/yuu0w0/n/nf71d14e03c8d )

---

# 組み合わせにお勧めの衣装
 - [【白星アバター向け着せ替え衣装】水着／ビキニ（VRChat用）] ( https://booth.pm/ja/items/1733108 )
* かすたちゃんの場合はY Positionを-0.0323にする *

 - [ 【こまどアバター対応】みずぎコレクション ]( https://sugary-boutique.booth.pm/items/3057397 )

 - [ 【3Dモデル】フロントロック水着 ]( https://booth.pm/ja/items/2766229 )

---

# 導入方法
## 導入方法 (ModularAvater対応衣装の場合)
*手順1*

  1. **Modular Avatar**の最新版をインストールしていない場合はインストールをして下さい. [Modular Avatar]( https://modular-avatar.nadena.dev/ja/ )
  2. "**SVST02_05_VRC_Light**"をHierachyにD&D
  3. KL_SHOP > CasualAndCoolJacket > Prefab > SVST02 内にある"**jacketSet_SVST02_MA**"を"SVST02_05_VRC_Light"に直接D&D

完了!

## 導入方法(ModularAvater未対応版,ModularAvaterを使用しない場合)
*CustaChanを例にして記述* 
**VRCSDK2 Or VRCSDK3(Avatar)をインポートしている必要があります**
[VRCSDK] ( https://vrchat.com/home/download )

1. CasualAndCoolJacket_x_x.x.unitypackageをインポート.
   後からアバターをインポートする場合,アバターに同梱しているシェーダーが古い可能性があり,ジャケットのシェーダーが正しく表示されなくなることがあります.
   **その場合は,別途同梱しているシェーダーを上書きインポートするか,先にアバターをインポートしておいてください.**
   **シェーダーが正しく反映されない場合は,"OtherData.zip"に含まれるシェーダーをインポートしてください.**
2. SceneにCustaChanのPrefabと**KL_SHOP > CusualAndCoolJacket > Prefab > CustaChan**内にあるPrefabを,必要であればMaterialフォルダ内のマテリアルを好きな組み合わせで適用してください.
3. アバターとジャケットで右クリック → Unpack Prefab
4. CustaChanのRootNode配下にある"Hoodie","HoodleCap"を削除,または非表示にする.BodyもFullBodyのテクスチャに変更.シェイプキーで肩など隠している場合は表示させましょう.
5. (Auto Dresserを使わない場合) ウェアのボーンをそれぞれ,アバターの同名ボーンの中に移動させる.(指のボーンにはウェイトが乗ってないので入れ子にしなくて大丈夫です)
   (Auto Dresserを使う場合) **予め"Auto Dresser"をインポートしておいてください.** UnpackしたウェアのInspectorにて"Auto Dresser"をAdd Componentから追加します."Auto Dresser"の"Cloth HipBone"にUnpackしたウェア,"Body Object"にCustaChanをDDし,"Dressing On"で完了です.

---

# 色の改変について
 - マテリアル内の色味のある項目を弄るとある程度変わります.
  - 色の影響が強い項目は以下の順です.
   1. Main Texture(色と画像)とその下のChColor1～3(色のみ),Shadowの1st/2nd shade(色と画像),Is Double Sided(裏面の項目です.HueShiftに関しては一部のワールドで違う色になってしまうので0にしてあります)
   2. RimLight
   3. Parallaxd Emission(ビニール素材の部分なので,Cyberマテリアルで特に目立ちます)
   4. MatCap,Gloss(ワールドによってはそもそも出なかったりしますが,MufflerとKnitte_redで有彩色が入ってるので一応見てみて下さい)

---

# 各リンク

## シェーダー
 - [ Arktoon-Shaders ]( https://booth.pm/ja/items/1027997 )
 - [ 3チャンネル式ArktoonアドオンK2Ex_3CH ]( https://kuukuukon.booth.pm/items/1582115 )

## マスク画像・MatCap等
 - [ Arktoon-Shaders 付属素材・PoiyomiToonShader 付属素材 ]( https://github.com/poiyomi/PoiyomiToonShader )
 - [ Unlit_WF_ShaderSuite 付属素材 ]( https://github.com/whiteflare/Unlit_WF_ShaderSuite )
 - [ PBT-Shader 付属素材 ]( https://booth.pm/ja/items/1266870 )

### マフラー柄
 - [ 可愛い秋冬のチェック柄セット【透過布地素材】]( https://assets.clip-studio.com/ja-jp/detail?id=1799925 )

### 毛糸柄
 - [ Fablic_Knitted_002(CC0) ]( https://3dtextures.me/2020/03/17/fabric-knitted-002/ )

---

# 規約
- 再配布,再販不可
- 改変可
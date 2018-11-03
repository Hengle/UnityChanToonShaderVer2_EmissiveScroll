﻿<p>README.md</p>

<h1>【ユニティちゃんトゥーンシェーダー Ver.2.0.5】</h1>

<p>「ユニティちゃんトゥーンシェーダー」は、セル風3DCGアニメーションの制作現場での要望に応えるような形で設計された、映像志向のトゥーンシェーダーです。</p>
<p>ユニティちゃんトゥーンシェーダーVer.2.0では、従来の機能に加えて大幅な機能強化を行いました。<br>Ver.1.0でできる絵づくりをカバーしつつ、さらに高度なルックが実現できるようになっています。</p>

<h2>【Unity-Chan Toon Shader Ver.2.0.5】</h2>

<p>Unity-Chan Toon Shader is a toon shader for video and images that is designed to meet your needs when creating cel-shaded 3DCG animations.</p>
<p>We have greatly enhanced the performance and features in Unity-Chan Toon Shader Ver. 2.0.<br>It still has the same rendering capabilities as Ver. 1.0, but now you can give your creations an even more sophisticated look.</p>
<hr>

<h2>【ターゲット環境】</h2>

<p>Unity5.6.x もしくはそれ以降が必要です。Unity 2018.1.0f2以降でも使用できます。<br>本パッケージは、Unity5.6.3p1で作成されています。</p>

<h3>【Target Environment】</h3>

<p>Requires Unity 5.6.x or later. Available on Unity 2018.1.0f2 or lator, too.<br>This pack was created in Unity 5.6.3p1.</p>
<hr>

<h2>【提供ライセンス】</h2>

<p>「ユニティちゃんトゥーンシェーダーVer.2.0」は、UCL2.0（ユニティちゃんライセンス2.0）で提供されます。<br>ユニティちゃんライセンスについては、以下を参照してください。<br><a href="http://unity-chan.com/contents/guideline/">http://unity-chan.com/contents/guideline/</a></p>

<h3>【License】</h3>

<p>Unity-Chan Toon Shader 2.0 is provided under the Unity-Chan License 2.0 terms.<br>Please refer to the following link for information regarding the Unity-Chan License.<br><a href="http://unity-chan.com/contents/guideline_en/">http://unity-chan.com/contents/guideline_en/</a></p>
<hr>

<h2>【インストールの注意】</h2>


<h3>UTS2_ShaderOnly_v2.0.5_Test.unitypackage</h3>

<p>新規インストールは、Unityにそのまま本パッケージをD&amp;Dすればインストールされます。<br>上書きインストール時には、コードが改修されていますので、注意が必要です。  </p>
<ol>
<li>元のプロジェクトのバックアップをとっておく  </li>
<li>Unityでプロジェクトを開き、新規シーンを作成して開いておく。  </li>
<li>元のトゥーンシェーダーが入っているフォルダ（Assets/Toon/Shader）をUnity上から削除する。  </li>
<li>本パッケージをUnityにD&amp;Dする。  </li>
</ol>
<p>まず元のシェーダーを消した後で、すぐに新しいシェーダーをインストールすれば、既存のマテリアルへのリンクは途切れないので、そちらでやってみてください。  </p>
<p>個人でみられる範囲でバグチェックはしていますが、何か不具合があったらご連絡よろしくお願いします。</p>

<h3>【Installation】</h3>


<h3>UTS2_ShaderOnly_v2.0.5_Test.unitypackage</h3>

<p>When installing for the first time, simply drag and drop this package into Unity to begin the installation process.  </p>
<p>When over-writing a previous version, the code will be revised, so please take the following precautions:  </p>
<ol>
<li>Back-up all previous projects.  </li>
<li>When opening a project in Unity, create a new scene beforehand.  </li>
<li>Erase the folder containing previous versions of the toon shader (Assets/Toon/Shader) from within Unity.  </li>
<li>Drag and drop this pack into Unity.  </li>
</ol>
<p>We recommend first erasing the previous shader then installing the new shader, to preserve existing links between materials.   </p>
<p>Please contact us if you have any issues. </p>
<hr>

<h2>【サンプルシーンについて】</h2>

<p>プロジェクトを開くと、以下のサンプルシーンがあります。  </p>
<p>・BoxProjection.unity：Box Projection を使った暗い部屋のライティング<br>・ToonShader.unity：イラストルックのシェーダー設定<br>・ToonShader_CelLook.unity：セルルックのシェーダー設定<br>・ToonShader_Emissive.unity：エミッシブを使ったシェーダー設定<br>・ToonShader_Firefly.unity：ビルトインライトと複数のリアルタイムポイントライト<br>・Baked Normal/Cube_HardEdge.unity：Baked Normalの参考<br>・Sample/Sample.unity：UTS2の基本シェーダーの紹介<br>・ShaderBall/ShaderBall.unity：シェーダーボールを使ってUTS2を設定する<br>・PointLightTest/PointLightTest.unity：ポイントライトを使ったセルルック表現のサンプル<br>・SSAO Test/SSAO.unity：SSAO in PPSのテスト用  </p>
<p>各シーンは、シェーダーやライティングの設定の参考用です。<br>作りたいルックやシーンの参考に役立つと思います。  </p>

<h3>【About Sample scenes】</h3>

<p>When you open this project, there are the following sample scenes.  </p>
<p>・BoxProjection.unity: For lighting settings to dark room using Box Projection<br>・ToonShader.unity: Illustration-like shader settings<br>・ToonShader_CelLook.unity: Cellook Shader settings<br>・ToonShader_Emissive.unity: Shader settings using Emissive<br>・ToonShader_Firefly.unity: built-in light and multiple real-time point lights<br>・Baked Normal / Cube_HardEdge.unity: Reference of Baked Normal<br>・Sample / Sample.unity: Introduction of basic shaders of UTS2<br>・ShaderBall / ShaderBall.unity: Set UTS2 using shader ball<br>・PointLightTest / PointLightTest.unity: Sample of CelLook style using point lights<br>・SSAO Test / SSAO.unity: For testing SSAO in PPS  </p>
<p>Each and every scenes are for reference of shader and lighting settings.<br>They will be useful for reference of the look and scene you want to make!  </p>
<hr>

<h2>【新規】</h2>


<h3>2018/10/06：2.0.5 Test：以下の機能追加と仕様変更をしました。</h3>


<h3>●【重要】BaseMapの内部変数名を変更しました。</h3>

<p>PostProcessing Stackに搭載されているSSAOでの不具合対処のために、BaseMapの内部変数名(<code>_BaseMap</code>)を<code>_MainTex</code>に変更しました。  </p>
<p>また.shaderファイルのプロパティブロックに以下の行を追加しました。<br><code>[HideInInspector] _Color (&quot;Color&quot;, Color) = (1,1,1,1)</code><br>元のSSAOの結果に戻したい時には、適宜コメントアウトしてください。  </p>

<h3>●Forward Addパス内で主にポイントライトのシェードステップを調整する、Step_Offsetスライダーを追加</h3>

<p>BaseColor_Step、ShadeColor_Step、1st_ShadeColor_Step、2nd_ShadeColor_Stepでの設定に加えて、Step_Offsetでさらに微調整を加えることで、特にセルルック時でのポイントライトの調整ができるようになりました。  </p>

<h3>●アドバンス機能として、Built-in Light Directionを追加</h3>

<p>上級者向け機能として、シェーダー内にビルトインされているライトディレクションベクトルを任意の方向に設定できるようにしました。<br>Built-in Light Directionを有効にしたマテリアルは、それが適応されるメッシュのオブジェクト座標に対して、独自のシェーディング用ライトディレクションベクトルを持つことができるので、専用の固定ライトを持つことと同じ効果が得られます。そのパーツが落とすドロップシャドウは、シーン中のディレクショナルライトを使いますので、シェーディングの落ち方とドロップシャドウの落ち方を変えることもできます。<br>Built-in Light Directionのライトカラーは、シーン中のメインとなるディレクショナルライトの設定を使います。  </p>

<h3>●以下の修正をしました。</h3>

<p>・一部のプロパティの並び順を、より作業しやすいように入れ替えしました。<br>・シーン中のアンビエントカラーの取得方法を変更し、よりシーン全体のアンビエントライトのカラーを反映するようにしました。  </p>
<hr>

<h3>2018/09/10：2.0.4.3 Release Patch 1：バグフィックス版</h3>

<p>・スポットライトが正常に使えなかったのを修正しました。<br>・リアルタイムポイントライトがレンジおよび距離に対し、正しく減衰するように修正しました。<br>・修正が確認されましたので、iOS/OSX METAL環境での注意を削除しました。  </p>

<h3>2018/09/05：2.0.4.3 Release：以下の修正と追加をしました。特にVRChat向けに便利な機能を搭載しています。</h3>


<h3>●アンビエントライトブレンディングを搭載</h3>

<p>アンビエントライトの設定をライトカラーが反映するようになりました。<br>その結果として、ディレクショナルライトのインテンシティの下限が、シーンのアンビエントライトの設定となります。　　<br>VRChatで、アンビエントライトの設定に基づくワールドごとの明るさの差異を自動で調整できます。<br>なおアンビエントライトからの明るさは、Unlit_Intensity スライダーで調整することもできます。デフォルトは 1（そのまま）になっています。  </p>

<h3>●カメラ追従型のデフォルトライトを搭載</h3>

<p>ディレクショナルライトがシーン中にない場合、シェーダーに組み込まれたデフォルトライトが有効になりますが、その向きが常にカメラに追従するようになりました。<br>結果、カメラから見て常に良い感じにライティングされるようになりました。  </p>

<h3>●Baked Normal for Outline搭載</h3>

<p>頂点法線を焼き付けたノーマルマップを、法線反転アウトラインの設定時に読み込むことができるようになりました。本機能を使うことで、ハードエッジのオブジェクトに、ソフトエッジのオブジェクトのアウトラインを、事前にベイクしたノーマルマップを経由して適用することができるようになります。  </p>
<p>Baked Normalマップを使用する時には、UTS2のアウトライン設定プロパティで、  </p>
<ol>
<li>OUTLINE MODE を &quot;NML&quot; に  </li>
<li>Is_BakedNormal を &quot;ON&quot; に  </li>
<li>Baked Normal for Outline に使用したいマップを適用します。 </li>
</ol>
<p>Baked Normal for Outline として適用できるノーマルマップは以下のような仕様となっています。  </p>
<ol>
<li>適用するオブジェクトの UV は重ならないこと。つまり、全てのノーマルマップが重ならないように UV 展開がされていることが必須です。  </li>
<li>ノーマルマップ自体の仕様は、Unity と同じで、OpenGL 準拠となります。  </li>
<li>使用するノーマルマップのテクスチャ設定は、以下のようになります。<br>・Texuture Type は &quot;Default&quot; にする。※ &quot;Normal map&quot; に設定してはいけません。<br>・sRGB (Color Texture) を必ず &quot;OFF&quot; にする。  </li>
</ol>
<p>詳しくはサンプルプロジェクト内の Baled Normal フォルダ内のアセットを確認してください。</p>

<h3>●Helperフォルダ内にアウトラインオブジェクト表示専用シェーダーを追加</h3>

<p>シェーダーバリエーションとして、アウトラインオブジェクトのみを表示するシェーダーを Helper フォルダ内に追加しました。必要に応じてマルチマテリアルとしてお使いください。  </p>

<h3>●Forward Add パス内の処理の簡略化。他、バグフィックス</h3>

<p>Forward Add パス内の処理の簡略化を含め、処理の軽減化およびバグ修正をしました。 </p>
<hr>

<h3>2018/08/21：2.0.4.2 Release：以下の修正と追加をしました。</h3>

<p>VRChat内の鏡オブジェクトに表示した時、Offset_Camera_Zに不具合が発生するのを修正。<br>VRChat向けにMobile用クリッピングシェーダーのバリエーションを6つ追加。  </p>
<hr>

<h3>2018/08/16：2.0.4.2 Release：MatcapMaskを追加</h3>

<p>MatCapに、メッシュのUVベースで効果のかかり具合を調整できるMatcapMaskを追加。Matcapマスクは「白」ほど効果が出やすくなります。<br>Tweak_MatcapMaskLevelプロパティで強度が調整できます。  </p>
<hr>

<h3>2018/07/04：2.0.4.1 Release：Unlit_Intensityプロパティを追加</h3>

<p>シーン内に有効なライトがない場合に、UTS2がデフォルトのライティングに切り替えますが、その明るさを調整できるようにしました。<br>主にVR Chatでの特殊なシーン向けでの設定を想定しています。<br>シーン内に有効なディレクショナルライトがある場合には、本プロパティは影響はしません。</p>
<hr>

<h3>2018/05/04：2.0.4 Release：ターゲット環境を正式にUnity5.6.x以降としました。Unity2018.1.0f2にも対応しています。</h3>

<p>コードの全面的な改修およびバグ修正の他、以下の仕様を新規に追加しました。</p>

<h3>●UTS_EdgeDetection.unitypackage</h3>

<p>ポストエフェクトタイプのエッジ抽出フィルタです。<br>元々はUnityのStandard Assetsにあったものを改造したフィルタ3つに加えて、新規に作成したSobel Color Filterが追加されています。<br>Sobel Color Filterを使うことで、効果的にトゥーンラインエッジを強調し、セル画時代の色トレス風の雰囲気を出すことができます。<br>本ポストエフェクトは、ポストエフェクトスタックの前に入れるとよいと思います。</p>

<h3>●DX11 Phong Tessellation対応</h3>

<p>対応部分のコードは、Nora氏の <a href="https://github.com/Stereoarts/UnityChanToonShaderVer2_Tess">https://github.com/Stereoarts/UnityChanToonShaderVer2_Tess</a> を参考にさせていただきました。<br>Tessellationは、使えるプラットフォームが限られている上に、かなりパワフルなPC環境を要求しますので、覚悟して使ってください。<br>想定している用途は、パワフルなWindows10/DX11のマシンを使って、映像＆VR向けに使用することです。<br>Light版とあるものは、ライトをディレクショナルライト１灯に制限した代わりに軽量化したバリエーションです。  </p>

<h3>●Positionスケーリングベースのアウトラインを搭載。</h3>

<p>従来の法線反転方式だとアウトラインが切れてしまう、キューブのようなモデルに綺麗にアウトラインが出せます。  </p>

<h3>●クリッピング系シェーダーでアウトラインのアルファ抜きに対応。</h3>

<p>アルファ付きテクスチャと組み合わせた時に、背面から見てもアウトラインポリゴンがアルファに従って抜けるようにした。  </p>

<h3>●アウトライン用テクスチャ（Outline_Tex）の搭載。</h3>


<h3>●ハイカラー用テクスチャ（HiColor_Tex）の搭載。</h3>


<h3>●PostProcessingStackと一緒に使うことを前提に、エミッシブカラー（Emissive_Color）およびエミッシブ用テクスチャ（Emissive_Tex）を搭載。</h3>

<p>エミッシブカラー側でHDR値が設定できるので、PostProcessingStackのブルームエフェクトと組み合わせることで、エミッシブ部分を光らせることができるようになった。<br>※今回搭載された新規テクスチャに関しても、今まで通り、必要なければ使わなくても問題ないようになっています。  </p>

<h3>●VR Chatに対応</h3>

<p>シーン内に有効なライトが存在しない場合（シーン内にライトオブジェクトがない場合と、ライトのインテンシティが0.001以下の場合を含みます）、デフォルトの明るさで照らされます。<br>なおVR Chat向けには、システムへの負荷を考慮してMobileフォルダ内のシェーダーを使うことをお勧めします。その場合、ライトは1灯のみの対応となります。</p>
<hr>

<h2>【Version】</h2>


<h3>2018/10/06: 2.0.5 Test：Added new features below.</h3>


<h3>【Caution】The internal variable name of BaseMap had been changed.</h3>

<p>The internal variable name of BaseMap(<code>_BaseMap</code>) had been changed into <code>_MainTex</code> in order to fix the problems with SSAO in PostProcessing Stack.  </p>
<p>Also added the following line to the property block of the .shader file.<br><code>[HideInInspector] _Color (&quot;Color&quot;, Color) = (1, 1, 1, 1)</code><br>If you want to return to the original SSAO result, comment out as appropriate.  </p>

<h3>●Add Step_Offset slider to adjust the shade stepping of the point lights mainly in the Forward-Add path.</h3>

<p>In addition to the settings in BaseColor_Step, ShadeColor_Step, 1st_ShadeColor_Step,and 2nd_ShadeColor_Step, you can now fine-tune the shade stepping with Step_Offset to adjust the shading with point lights especially at cel-look style.  </p>

<h3>●Advanced function : Add Built-in Light Direction</h3>

<p>As the function for advanced users, you can now set the built-in light deirection vector within shader to your favorite direction.<br>The material enabled Built-in Light Direction can have its own light deirection vector in the object coordination of the mesh, and shade it from as like as a fixed light. Drop shadow of the mesh has consistency with the directional light in the scene, so you can control how the shade falls and how the shadow dropps.<br>The color of Built-in Light Direction uses the setting of the main directional light in the scene.  </p>

<h3>●Made the following corrections.</h3>

<p>・Rearranged the order of some properties for your easier operation.<br>・Changed the method of getting the ambient color in the scene, and so shader becomes to reflect the color of the ambient light from the whole scene more.  </p>
<hr>

<h3>2018/09/10：2.0.4.3 Release Patch 1：Bug fix version.</h3>

<p>・Fixed the problem that spotlight could not work properly.<br>・Fixed real-time point light to attenuate correctly with respect to range and distance.<br>・Since bug-fixes were confirmed, the notes when using with iOS / OSX METAL environment were deleted.  </p>

<h3>2018/09/05: 2.0.4.3 Release：Fixed bug and added new features below. Especially, added useful features for VRChat users!</h3>


<h3>●Add Ambient light blending</h3>

<p>Light color now reflects ambient light settings.<br>As a result, the lower limit of the intensity of the directional light becomes the setting of the ambient light of the scene.<br>With VRChat, you can automatically adjust the brightness difference for each world based on ambient light settings.<br>The brightness from the ambient light can also be adjusted with the Unlit_Intensity slider. The default is 1 (as it is).  </p>

<h3>●Equipped with camera following type default light</h3>

<p>If the directional light is not in the scene, the default light built in the shader is enabled, and its orientation always follows the camera.<br>As a result, you always keep good lighting from the view of camera.  </p>

<h3>●Add Baked Normal for Outline</h3>

<p>You can now use normal maps baked vertex normals when setting normal-inversion outlines. By using this feature, you can apply the outline of the soft edge object to the hard edge object via the pre-baked normal map.  </p>
<p>When using the Baked Normal map, in the outline setting property of UTS2:  </p>
<ol>
<li>OUTLINE MODE is &quot;NML&quot;,  </li>
<li>Is_BakedNormal is &quot;ON&quot;,  </li>
<li>Apply the map you want to use for &quot;Baked Normal for Outline&quot; slot.  </li>
</ol>
<p>Normal map applicable as Baked Normal for Outline has the following specifications.  </p>
<ol>
<li>The UV of the object to be applied shall not overlap. In other words, it is essential that UV deployment is done so that all normal maps do not overlap.  </li>
<li>The specification of the normal map itself is the same as Unity, it is OpenGL compliant.  </li>
<li>The texture settings of the normal map to be used are as follows.<br>· Set Texuture Type to &quot;Default&quot;. ※ Do not set to &quot;Normal map&quot;.<br>· Be sure to turn OFF sRGB (Color Texture) check.  </li>
</ol>
<p>For details, please check the assets in the Baled Normal folder in the sample project.</p>

<h3>●Add the shaders for outline object display only, in Helper folder</h3>

<p>As the shader variations, add the shader that displays only outline objects in Helper folder. Please add them as multi-materials as necessary.  </p>

<h3>●Simplify processing within the Forward Add path. Other, bug fixes</h3>

<hr>

<h3>2018/08/21: 2.0.4.2 Release：Fixed bug and added shader variations.</h3>

<p>Fixed Offset_Camera_Z bug with mirror objects in VRChat.<br>Added 6 shader variations to Mobile/_Clipping series for VRChat.  </p>
<hr>

<h3>2018/08/16: 2.0.4.2 Release:Add MatcapMask.</h3>

<p>Added MatcapMask that can adjust the power of MatCap effect applied on the UV base of the mesh. MatcapMask is a grayscale map, &quot;white&quot; becomes to MatCap full effect.<br>You can adjust the power of the mask with Tweak_MatcapMaskLevel property.  </p>
<hr>

<h3>2018/07/04: 2.0.4.1 Release:Add Unlit_Intensity property.</h3>

<p>If there is no valid light in the scene, UTS2 switches to default lighting, and now you can adjust its brightness.<br>This property is assuming for using in special scenes mainly in VR Chat.<br>If there is a valid directional light in the scene, this property will not be affected.</p>
<hr>

<h3>2018/05/04: 2.0.4 Release: Officially set Unity5.6.x and later versions as the target environment. Unity2018.1.0f2 is also supported.</h3>

<p>In addition to overall code revisions and bug fixes, the following has been added to this new version. </p>

<h3>●UTS_EdgeDetection.unitypackage</h3>

<p>This is an edge extraction filter of post effect type.<br>This package includes three modified filters modified from Unity&#39;s Standard Assets,and a newly created Sobel Color Filter.<br>By using Sobel Color Filter, you can effectively emphasize the toon line edge and give out the color tress-like atmosphere of the cell picture era.<br>Attach this post effect before the post-effect-stack.</p>

<h3>●DX11 Phong Tessellation support</h3>

<p>The supporting code referenced Nora&#39;s work <a href="https://github.com/Stereoarts/UnityChanToonShaderVer2_Tess">https://github.com/Stereoarts/UnityChanToonShaderVer2_Tess</a><br>Please be aware that only certain platforms support tessalation and it requires a considereably powerful PC environment.<br>It is intended for use in video, images, and VR on powerful Windows10/DX11 machines.<br>The &quot;light version&quot; uses lighter weight variation instead of limiting the directional lighting to 1 source.   </p>

<h3>●Base outlines for Position Scaling</h3>

<p>In previous versions, outlines would be broken by the vector inversion formula, now you can cleanly outline models like cubes</p>

<h3>●Support for clipping shaders with outlines that don&#39;t have an alpha</h3>

<p>When paired with textures that have an alpha, the outline polygons will be removed according to the alpha, even when viewed from behind. </p>

<h3>●Outline textures (Outline_Tex)</h3>


<h3>●HiColor textures (HiColor_Tex)</h3>


<h3>●Assuming this shader will be used together with PostProcessingStack, Emissive Color (Emissive_Color) and Emissive Textures (Emissive_Tex)</h3>

<p>HDR values can be set on the Emissive Color side, allowing the Emissive portion to shine when combined with PostProcessingStack&#39;s bloom effect.<br>※As always, using these new textures is not required.   </p>

<h3>●VR Chat ready!</h3>

<p>If there is no valid light in the scene (including the case where there is no light object in the scene and the intensity of the light is less than 0.001), objects will be illuminated with the default brightness.<br>For VR Chat, we recommend using shaders in the Mobile folder in consideration of the load on the system. In that case, the light will correspond to only one light.</p>
<hr>

<h2>【過去の修正履歴】</h2>

<p>2017/06/19：2.0.3：Set_HighColorMask、Set_RimLightMaskの追加。機能強化の結果、Set_HighColorPositionは廃止。<br>2017/06/09：2.0.2：Nintendo Switch、PlayStation 4に正式対応。モバイル軽量版の追加。その他機能強化。<br>2017/05/20：2.0.1：TransClipping系シェーダーのブレンド仕様変更とリムライトに調整機能追加。<br>　　　　　　　　　 上の仕様変更に伴い、トランスペアレント系シェーダーを２つ追加。<br>　　　　　　　　　（ToonColor_DoubleShadeWithFeather_Transparent、ToonColor_ShadingGradeMap_Transparent）<br>2017/05/07：2.0.0：最初のバージョン  </p>

<h3>【Version Update History】</h3>

<p>2017/06/19: 2.0.3: Added Set_HighColorMask and Set_RimLightMask, as a result of these improvements Set_HighColorPosition was removed.<br>2017/06/09: 2.0.2: Official support for Nintendo Switch and PlayStation 4. Added lightweight version for mobile. Various other improvements<br>2017/05/20: 2.0.1: Modified the blend methods for TransClipping shaders and added rim light regulation function.<br>In addition to the above modifications, added 2 transparent shaders (ToonColor_DoubleShadeWithFeather_Transparent, ToonColor_ShadingGradeMap_Transparent)<br>2017/05/07: 2.0.0: Initial version   </p>
<hr>
<p>最新バージョン：2.0.5<br>最終リリース日：2018/10/06<br>カテゴリー：3D<br>形式：zip  </p>
<p>Latest Version: 2.0.5<br>Update: 2018/10/06<br>Category: 3D<br>File format: zip  </p>

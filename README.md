## Canopy Dynamics : Regional study in Hong Kong of the Green View Index changes from Google Street view imageries

Guided question : “How can we quantify the changes and greening efforts led by the TMO?” 

Google Street View has been conducting mobile mapping campaigns since 2009, and the captured images are freely available for open-source applications. These images offer a unique, pedestrian-level perspective that enables us to trace vegetation changes over time in a close-range format. This makes it easier to quantify and understand trends using the Green View Index (GVI), GVI is a measure of the proportion of visible vegetation captured from street-level imagery. 

To derive the GVI, the Street View images are first tiled into panoramic views and then split into four segments for semantic segmentation. The segmented results produced by a pre-trained fine tuned model serve as the basis for computing the GVI. Because panoramic images are often distorted, we can't calculate the GVI directly from them. To address this, a weighting scheme is applied to compute uniform pixel values, allowing for accurate evaluation of vegetation cover.

The GVI results are mapped and displayed on an interactive interface. This enables users to visually explore and compare vegetation changes over time using both the segmented masks and the original images.

GVI Interactive map : https://ottoykh.github.io/treepedia/map/gvi.html 

Google Street View images are copyrighted by Google.

### 粵語版 Cantonese version 
我哋可以點樣量化城市綠化同變化？

自 2009 年起，Google Street View 一直進行移動地圖拍攝，其拍攝嘅街景影像已公開和開源應用。呢啲影像提供咗一個獨特、以行人視角為本嘅觀察方式，方便我哋近距離追蹤植被隨時間嘅變化，有助於利用「綠化視覺指數（GVI）」來量化並理解呢啲趨勢。

GVI 係一個衡量街景影像中可見綠化比例嘅指標。

為咗計算 GVI，街景影像首先會被拼接成全景圖，然後分成四段，進行語義分割。透過一個已預訓練並微調過嘅模型，我哋可以獲得分割結果，進而作為計算 GVI 嘅基礎。由於全景圖像有時會出現扭曲，直接用嚟計算 GVI 並唔準確，因此我哋應用咗一個加權算法，令像素計算更平均，從而準確評估植被覆蓋率。最後，計算出嚟嘅 GVI 結果會以互動地圖方式展示，用戶可以透過遮罩圖層同原始影像，直觀地探索唔同時間段內嘅綠化變化。

綠化視覺指數GVI互動地圖: https://ottoykh.github.io/treepedia/map/gvi.html 

Google街景圖像版權歸Google所有。


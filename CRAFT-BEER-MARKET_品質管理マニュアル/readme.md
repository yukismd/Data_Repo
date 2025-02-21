# CRAFT-BEER-MARKET 品質管理マニュアル

### CRAFT BEER MARKET 品質管理マニュアル(https://www.craftbeermarket.jp/wp2/wp-content/themes/cbm/images/pdf/cbm_quality_management_manual_v01.pdf) RAG実験データセット

**(1) Original**: [cbm_quality_management_manual_v01.pdf](cbm_quality_management_manual_v01.pdf)  

**(2) txt化したデータ**: [doc_outputs/markitdown_default.txt](doc_outputs/markitdown_default.txt)
- markitdown[code/markitdown.ipynb](code/markitdown.ipynb)を利用

**(3) markitdown_default.txtの成形版**: [doc_outputs/markitdown_structured.txt](doc_outputs/markitdown_structured.txt)
- markitdown_default.txtを手作業で成形
- 画像（[images](images)）はVLMで説明文を作成（[code/gpt4o-min_image_description.ipynb](code/gpt4o-min_image_description.ipynb)）。説明内容は、<'画像ファイル名'の写真>タグで記述

**(4) markitdown_structured.txtの分割版**: [doc_outputs/CRAFT-BEER-MARKET_品質管理マニュアル_txt](doc_outputs/CRAFT-BEER-MARKET_品質管理マニュアル_txt)
- markitdown_structured.txtを各章別にファイル分割
